Lynn Li (ll643) and Allison Tran (ant42)
Group 3
Reactor Characteristics Prelab

#### Question 1: Calculate the change in hydraulic grade line between baffled sections of a reactor with a flow rate of 380 mL/min. The reactor baffles are perforated with 6 holes 1 mm in diameter. Is the flow through these orifices in series or in parallel? Do you multiply the head loss for one orifice by the number of orifices to get the total head loss? Are the orifices in parallel or in series? Use the pc.head_orifice function to calculate the head loss through an orifice. The vena contracta for the orifice can be found at aguaclara.core.constants.VC_ORIFICE_RATIO. Why would 6 holes 1 mm in diameter not be a good design for this reactor?

Equations:

$Q_{reactor} =n_{orifice} K_{orifice} \frac{\pi d_{orifice}^{2} }{4} \sqrt{2g\Delta h}$ (83 from Lab Manual)

$\Rightarrow Q_{orifice} =n_{orifice}K_{orifice} A_{orifice} \sqrt{2g\Delta h} $

$\Rightarrow \Delta h = \frac{(\frac{Q_{orifice}}{n_{orifice}K_{orifice}A_{orifice}})^2}{2g}$

The flow through these orifices are in parallel because the flow would go thorough all of the orifices at once. The orifices themselves are in parallel as well. Since the orifices are in parallel, we do not multiply the head loss for one orifice by the number of orifices to get the total head loss. This can be explained by the fact that each water molecule only goes through one orifice per baffled section so each molecule would only experience head loss once for per baffled section. Therefore the total head loss would be the head loss through one orifice. This design would not be good for this reactor because the head loss is too large which could cause an overflow in the reactor.

```python
import aguaclara
from aguaclara.core.units import unit_registry as u
import math as m
import aguaclara.core.physchem as pc
u.define('equivalent = mole = eq')
import aguaclara.research.environmental_processes_analysis as epa
from scipy import optimize
from scipy import stats
from aguaclara.core import utility as ut
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
Q = (380*(u.mL/u.min)).to(u.m**3/u.s)
Number_Holes = 6
Gravity = aguaclara.core.constants.GRAVITY
Diameter = (1*(u.mm)).to(u.m)
#"The hydraulic grade line (and thus depth of each baffled reactor) will drop by a distance equal to the head loss through the pores" (Lab Manual)
Ratio = aguaclara.core.constants.VC_ORIFICE_RATIO
Head_Loss = pc.head_orifice(Diameter,Ratio,Q)
print('The change in hydraulic grade line between baffled sections is',ut.round_sf(Head_Loss,5), '.')
#The change in hydraulic grade line between baffled sections is 8.353 meter
```

#### Question 2: On a single graph plot the exit age distribution (E(t⋆)) for a reactor that operates as a 1-dimensional advection-dispersion reactor with Peclet numbers of 1, 10, and 100 (there will be three plots on the graph and thus a legend is required). The x-axis should be t⋆ from 0.0 to 3.0. Comment on the shapes of the curves as a function of the Peclet number. Note that the advective dispersion equation is undefined for t⋆=0. Use the epa.E_Advective_Dispersion(t,Pe) function.
```python
Pe_1 = 1
Pe_2 = 10
Pe_3 = 100
t = np.arange(0.1, 3.1, 0.1)
plot_1 = np.zeros(30)
for i in range (len(t)):
  plot_1[i]= epa.E_Advective_Dispersion(t[i],Pe_1)
plot_2 = np.zeros(30)
for i in range (len(t)):
  plot_2[i]= epa.E_Advective_Dispersion(t[i],Pe_2)
plot_3 = np.zeros(30)
for i in range (len(t)):
  plot_3[i]= epa.E_Advective_Dispersion(t[i],Pe_3)
plt.plot(t, plot_1, label='Pe 1')
plt.plot(t, plot_2, label='Pe 10')
plt.plot(t, plot_3, label='Pe 100')
plt.xlabel('t⋆ (dimensionless)')
plt.ylabel('E(t⋆) (dimensionless)')
plt.legend()
plt.title('E(t⋆) vs Time')
plt.show()
```
![Figure1](https://github.com/ll643/Lab-5/blob/master/group3_reactor_prelab.png)

Figure 1: Graph of E(t⋆) vs Time for an array of t⋆ from 0.0 to 3.0 with three different Pe values

As the Pe values increase by 10 fold, the curves become much narrower and steeper. Also, the magnitude of the maximum peak becomes much larger.
