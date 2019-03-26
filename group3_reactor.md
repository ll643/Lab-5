# Reactor Lab
#### Lynn Li (ll643) time spent: 10
#### Allison Tran (ant42) time spent: 10
#### Group 3
#### Due 03/26/2019


# Introduction and Objectives
The goal of this experiment was to simulate a chlorine contactor tank and maximize the amount of time that the water flow spent in the tank, referred to as the contact time. In chlorine contactor tanks, the contact time must be maximized to allow for the chlorine to come into contact with as many of the pathogens and pollutants in the water as possible for disinfection. We modeled this chlorine contactor tank on a smaller scale using a basin of water, baffles to modify the flow of water, and red dye to mimic the pathogens and pollutants coming into the basin through the influent. A peristaltic pump drew water into the tank at a steady rate, and drew water out through a photometer to quantitatively measure the concentration of red dye at the effluent. From this experiment, we were looking to study the impact of the baffles we chose on the time it took to filter the red dye through the basin. This setup could have potential implications for modeling and making predictions for the efficiency of a real-world chlorine contactor tank, by adding or modifying baffles in the tank to maximize the contact time.

### Equations
$F_{\left(t^{\star} \right)} =\int _{0}^{t^{\star} }E_{\left(t^{\star} \right)} dt^{\star}$ (Eq 1: used to graph the F curves from the E curves)

$\bar{t}=\; \frac{\sum _{i=0}^{n}t_{i} \cdot C_{i}  \Delta t}{\sum _{i=0}^{n}C_{i}  \Delta t}$ (Eq 2: used to calculate t_bar from which dead volumes can be determined)

# Procedures
Before starting the reactor lab, we calibrated the photometer. In order to achieve this, we made six calibration standards of: 0mg/L, 10mg/L, 20mg/L, 30mg/L, 40mg/L, 50mg/L. These standards were created by mixing 100mL of water in a beaker with 0 microL, 100 microL, 200 microL, etc. After calibrating the photometer we then set up the lab apparatus following the "Setting up the reactor for experiments" section of lab manual (Lab Manual). To test the apparatus, we tested a CMFR. We wanted a maximum concentration of around 30 mg/L, therefore, we needed to use the CMFR equation (Equation ) to find the appropriate amount of red dye that needed to be added to the basin given the volume of the water. In order to determine the volume of water in the basin, we took a ruler and measured the dimensions of the basin and the dimensions of the water in the basin. The dye was injected into the basin at the same time that ProCoDa started recording the photometer readings and the system was left on until the majority of the tracer had exited.

After the CMFR experiment, we started our three independent trials. The first trial involved one baffle which was placed exactly in the middle of our basin with 15.5cm between each baffle; the second with two baffles (of the same kind) also evenly spaced with 10.3cm between each baffle; and the third with three baffles (if the same kind) also evenly spaced with 7.75cm between each baffle. These baffles were tapped down on both sides with gorilla tape and along the bottom as well so that we could insure that the water was only going through the holes. For each of these three trials, the photometer was placed in the section of the basin that contained the effluent discharge port and no stir bar was implemented. For all three trials we injected 1mL of red dye at a concentration of 10 mg/L.

![Picture 1](https://github.com/ll643/Lab-5/blob/master/group3_pic1.jpg)

Picture 1: Picture of the start of our three baffle experiment

![Picture 2](https://github.com/ll643/Lab-5/blob/master/group3_pic2.jpg)

Picture 2: Picture of the middle of our three baffle experiment

![Picture 3](https://github.com/ll643/Lab-5/blob/master/group3_pic3.jpg)

Picture 3: Picture of baffles used in the experiment

# Results and Discussion
### Graphs
![Figure 1](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure1.png)

Figure 1: Plot of Concentration vs Time through a CMFR

![Figure 2](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure2.png)

Figure 2: Plot of Concentration vs Time through a Reactor with One Baffle

![Figure 3](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure3.png)

Figure 3: Plot of Concentration vs Time through a Reactor with Two Baffles

![Figure 4](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure4.png)

Figure 4: Plot of Concentration vs Time through a Reactor with Three Baffle (data untrimmed)

![Figure 5](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure5.png)

Figure 5: Plot of Concentration vs Time through a Reactor with Three Baffles (data trimmed)

![Figure 6](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure6.png)

Figure 6: Plot of Concentration Fraction vs Time through a Reactor with One Baffle (F curve)

![Figure 7](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure7.png)

Figure 7: Plot of Concentration Fraction vs Time through a Reactor with Two Baffles (F curve)

![Figure 8](https://github.com/ll643/Lab-5/blob/master/group3_reactor_figure8.png)

Figure 8: Plot of Concentration Fraction vs Time through a Reactor with Three Baffles (F curve; data trimmed)


We analyzed our findings for all components of this lab by plotting concentration and time. For the graph in which we plotted the CMFR data, our measured dye fit the CMFR model accurately (Figure 1). In the first experimental setup with just one baffle, our data most closely resembled the CMFR model at first, due to the initial spike in concentration (Figure 2). However, throughout the experiment, the data resembled both the CMFR model and the AD model closely. In our second experimental set up with two equally-spaced baffles, our data closely resembled both the CMFR model and the AD model (Figure 3). In our last experimental setup with three baffles, our data loosely resembled both the CMFR model and the AD model initially, through the initial spike in concentration. However, we experienced technical difficulties with this setup, and the concentration ended up dropping only to spike again unexpectedly (Figure 4). For this reason, we chose to trim the data after the first drop in concentration, to cut out any data that was skewed from experimental error such as pipetting. Once we trimmed and graphed the data, our experimental set up closely resembled both the CMFR model and the AD model (Figure 5).

For one baffle, our Pe value was 2.0589. For two baffles, our Pe value was 11.6113. For three baffles, our Pe value was 5.0011. The Peclet number is the ratio of advective to dispersive transport. In the limiting cases when Pe = 0 (very high dispersion) we have a CMFR and when Pe=∞, Dd = 0, no dispersion, we have a plug flow reactor (Lab Manual). When we went from one baffle to two baffles it decreased dispersion; however, we went from two baffles to three the dispersive increased again.

The value of t* at F = 0.1 for one, two, and three baffles are 95s, 130s, and 125s respectively. This did not meet our expectations because we expected a linear trend between the number of baffles and value of t* in the flocculator, and we therefore expected the t* value for three baffles to be higher than the t* value for two baffles.

If $\bar{t}$ is less than the hydraulic residence time it may indicate that the reactor contains “dead volume” or “short circuiting” such that some volume of the reactor is effectively unused (Lab Manual). The hydraulic residence time for the CMFR, reactor with one, two, and three baffles are 320.9677s, 325.3226s, 322.2581s, and 335.1613s respectively. In comparison, the average time spent in the reactor ($t_{bar}$) for the CMFR, reactor with one, two and three baffles are 278.3048s, 317.4199s, 236.9743s, and 236.9784s respectively. Therefore, the $t_{bar}$ value for each of our reactors is lower than its own respective residence time. From this we conclude that there is evidence of "dead volumes" or "short circuiting" in our reactors.

The parameter that we chose to vary as a part of our experimentation was the number of baffles. The design objective for chlorine contact tanks is to maximize the inactivation of pathogens by maximizing the contact time between the chlorine and the pathogens before the water is sent to the distribution system (Lab Manual). Therefore, after analyzing our reactor data, for the design of a full scale chlorine contact tank we recommend two baffles. This is due to the fact that the two baffle reactor resulted in the largest t* value. This will ensure that the Chlorine maximizes its time inside the contact tank.

# Conclusions
In conclusion, our experiment showed that our setup with two baffles was the most successful as a chlorine contactor tank. This is due to the fact that it had the largest t* value for when F = 0.1 (t* = 130 seconds). This means that the two baffle setup had the longest time period between when the original concentration was injected into the tank and when the concentration measured was 10% of the original. This meant that this setup would be the most effective as a chlorine contactor tank, as it would keep the influent in the tank as long as possible. In addition, the two baffle set up had the largest Pe value which means that it had the lowest value of dispersion. However, our set up with one baffle was the reactor with the lowest amount of dead volume because its t_bar value was closest with its residence time value. We were able to successfully recreate a chlorine contactor tank with red dye and water flow, and maximize the time the influent spent in the tank by adding baffles. The results of our experiment can be used when designing chlorine contactor tanks for real-world applications. Any inconsistencies can be attributed to a variety of human error, such as pipetting, ineffectively securing the baffles to the side of the tank, and air bubbles that may have been caught in the photometer.

# Suggestions/Comments
Overall, we enjoyed the Reactor lab. It was self-explanatory, straightforward, and easy to complete. Like the ANC lab, it was nice to be able to visually follow the process of the lab as it progressed. Our only suggestions would be in regard to installing the baffle. We had to redo our first trial because we were not aware that we had to tape down the sides of the baffles to the reactor. Adding on to that, if there was an easier way to tape down the baffles I think that would reduce a significant amount of frustration. When we had to install three baffles it was almost impossible to stick our hands in between the baffles to tape them down especially since the gorilla tape is so sticky. Thank you so much for designing this amazing lab!  

# Appendix
|     Attribute | Value    |   
|--------------:|----------|
|Dye Concentration|10mg/L|
|Reactor Length|31 cm|
|Amount of Dye|0.7 mL|
|Pump Rate|380 mL/min|

```python
import aguaclara
import os
from pathlib import Path
from aguaclara.core.units import unit_registry as u
import aguaclara.core.physchem as pc
u.define('equivalent = mole = eq')
import aguaclara.research.environmental_processes_analysis as epa
from scipy import optimize
from scipy import stats
from aguaclara.core import utility as ut
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import collections
from aguaclara.core import constants

#constants
total_L = 31*(u.cm)
density = constants.WATER_DENSITY
flow_mass = ((440-347)*(u.g)).to(u.kg)
flow_vol = flow_mass/constants.WATER_DENSITY
flow_vol = flow_vol.to(u.L)
Q = (flow_vol)/(15*u.s)

#CMFR constants
water_mass_CMFR = 2588*(u.g)-598*(u.g)
water_mass_CMFR = water_mass_CMFR.to(u.kg)
dye_CMFR = 0.7*(u.mL)

#Trial 1 constants
water_mass_1 = 2593*(u.g)-576*(u.g)
water_mass_1 = water_mass_1.to(u.kg)
dye_CMFR = 1*(u.mL)
distance_baffle_1 = 15.5*(u.cm)
one_vol = water_mass_1/constants.WATER_DENSITY

#Trial 2 constants
water_mass_2 = 2584*(u.g)-586*(u.g)
water_mass_2 = water_mass_2.to(u.kg)
dye_CMFR = 1*(u.mL)
distance_baffle_2 = 10.3*(u.cm)
two_vol = water_mass_2/constants.WATER_DENSITY

#Trial 3 constants
water_mass_3 = 2664*(u.g)-586*(u.g)
water_mass_3 = water_mass_3.to(u.kg)
dye_CMFR = 1*(u.mL)
distance_baffle_1 = 7.75*(u.cm)
three_vol = water_mass_3/constants.WATER_DENSITY
```
##### For CMFR
```Python
CMFR_path = 'https://raw.githubusercontent.com/ll643/Lab-5/master/group_3_no_baffle.xls'
epa.notes(CMFR_path)
CMFR_firstrow = epa.notes(CMFR_path).last_valid_index() + 1
CMFR_firstrow
CMFR_firstrow = CMFR_firstrow + 10
CMFR_time_data = (epa.column_of_time(CMFR_path,CMFR_firstrow,-1)).to(u.s)
CMFR_concentration_data = epa.column_of_data(CMFR_path,CMFR_firstrow,1,-1,'mg/L')
CMFR_V = (water_mass_CMFR/density).to(u.L)
CMFR_Q = Q.to(u.L/u.sec)
CMFR_theta_hydraulic = (CMFR_V/CMFR_Q)
CMFR_theta_hydraulic #320.9677419354839, 'second'
CMFR_C_bar_guess = np.max(CMFR_concentration_data)
CMFR_CMFR = epa.Solver_CMFR_N(CMFR_time_data, CMFR_concentration_data, CMFR_theta_hydraulic, CMFR_C_bar_guess)
CMFR_CMFR_model = CMFR_CMFR.C_bar * epa.E_CMFR_N(CMFR_time_data/CMFR_CMFR.theta,CMFR_CMFR.N)

#print statements
print('The model estimated mass of tracer injected was',ut.round_sf(CMFR_CMFR.C_bar*CMFR_V ,2) )
print('The model estimate of the number of reactors in series was', CMFR_CMFR.N)
print('The tracer residence time was',ut.round_sf(CMFR_CMFR.theta ,2))
print('The ratio of tracer to hydraulic residence time was',(CMFR_CMFR.theta/CMFR_theta_hydraulic).magnitude)
print('The model estimated mass of tracer injected was',ut.round_sf(CMFR_CMFR.C_bar*CMFR_V ,2) )
print('The model estimate of the number of reactors in series was', CMFR_CMFR.N)
print('The tracer residence time was',ut.round_sf(CMFR_CMFR.theta ,2))
print('The ratio of tracer to hydraulic residence time was',(CMFR_CMFR.theta/CMFR_theta_hydraulic).magnitude)

#plot
plt.plot(CMFR_time_data.to(u.sec), CMFR_concentration_data.to(u.mg/u.L),'r')
plt.plot(CMFR_time_data.to(u.sec), CMFR_CMFR_model,'b')
plt.xlabel(r'Time(s)')
plt.ylabel(r'Concentration $\left ( \frac{mg}{L} \right )$')
plt.legend(['Measured dye','CMFR Model'])
plt.title('Concentration vs Time CMFR')
plt.show()

#Calculate t_bar
numerator_CMFR = 0
denominator_CMFR = 0
firstNum_CMFR = CMFR_time_data[0];
lastNum_CMFR = CMFR_time_data[len(CMFR_time_data)-1]
delta_t_CMFR = lastNum_CMFR-firstNum_CMFR
for i in range(CMFR_time_data.size):
  numerator_CMFR = numerator_CMFR + ((CMFR_time_data[i])*(CMFR_concentration_data[i])*delta_t_CMFR)
  denominator_CMFR = denominator_CMFR + ((CMFR_concentration_data[i])*delta_t_CMFR)
t_bar_CMFR = numerator_CMFR/denominator_CMFR
t_bar_CMFR #278.3047683550709, 'second'
```
##### For One Baffle
```Python
one_baffle_path = 'https://raw.githubusercontent.com/ll643/Lab-5/master/group_3_one_baffle.xls'
one_baffle_firstrow = epa.notes(one_baffle_path).last_valid_index() + 1
one_baffle_time_data = (epa.column_of_time(one_baffle_path,one_baffle_firstrow,-1)).to(u.s)
one_baffle_concentration_data = epa.column_of_data(one_baffle_path,one_baffle_firstrow,1,-1,'mg/L')
one_baffle_concentration_data = one_baffle_concentration_data - one_baffle_concentration_data[0]
one_baffle_V = one_vol
one_baffle_Q = (Q).to(u.m**3/u.s)
one_baffle_theta_hydraulic = (one_baffle_V/one_baffle_Q) #325.3225806451612, 'second'
one_baffle_C_bar_guess = np.max(one_baffle_concentration_data)/2

#use solver to get the CMFR parameters
one_baffle_CMFR = epa.Solver_CMFR_N(one_baffle_time_data, one_baffle_concentration_data, one_baffle_theta_hydraulic, one_baffle_C_bar_guess)
one_baffle_CMFR.C_bar
one_baffle_CMFR.N
one_baffle_CMFR.theta.to(u.s)
one_baffle_CMFR_model = (one_baffle_CMFR.C_bar*epa.E_CMFR_N(one_baffle_time_data/one_baffle_CMFR.theta, one_baffle_CMFR.N)).to(u.mg/u.L)

#use solver to get the advection dispersion parameters
one_baffle_AD = epa.Solver_AD_Pe(one_baffle_time_data, one_baffle_concentration_data, one_baffle_theta_hydraulic, one_baffle_C_bar_guess)
one_baffle_AD.C_bar
one_baffle_AD.Pe
one_baffle_AD.theta
one_baffle_AD_model = (one_baffle_AD.C_bar*epa.E_Advective_Dispersion((one_baffle_time_data/one_baffle_AD.theta).to_base_units(), one_baffle_AD.Pe)).to(u.mg/u.L)

#print statements
print('The model estimated mass of tracer injected was',ut.round_sf(one_baffle_AD.C_bar*one_baffle_V ,2) )
print('The model estimate of the Peclet number was', one_baffle_AD.Pe)
print('The tracer residence time was',ut.round_sf(one_baffle_AD.theta ,2))
print('The ratio of tracer to hydraulic residence time was',(one_baffle_AD.theta/one_baffle_theta_hydraulic).magnitude)

#F curve
from scipy import integrate
from sklearn import preprocessing
y_int_1 = integrate.cumtrapz(one_baffle_concentration_data.to(u.mg/u.L), one_baffle_time_data.to(u.s), initial=0)
y_norm_1 = y_int_1/y_int_1.max(axis=0)
plt.plot(one_baffle_time_data.to(u.s), y_norm_1)
plt.xlabel('$Time (s)$')
plt.ylabel(r'Concentration Fraction (dimensionless)')
plt.legend(['Measured Dye'])
plt.title('Concentration Fraction vs Time for One Baffle')
plt.show()

#Finding t* when F = 0.1
def x_when_y(input,x,y):
  return (x[y.searchsorted(input)])
t_star_1 = (x_when_y(0.1,one_baffle_time_data,y_norm_1))
t_star_1 #(95.00459327999522, 'second')

#Plot the data and the two model curves
plt.plot(one_baffle_time_data.to(u.s), one_baffle_concentration_data.to(u.mg/u.L),'r')
plt.plot(one_baffle_time_data.to(u.s), one_baffle_CMFR_model,'b')
plt.plot(one_baffle_time_data.to(u.s), one_baffle_AD_model,'g')
plt.xlabel(r'$Time (s)$')
plt.ylabel(r'Concentration $\left ( \frac{mg}{L} \right )$')
plt.legend(['Measured Dye','CMFR Model', 'AD Model'])
plt.title('Concentration vs Time for One Baffle')
plt.show()

#Calculate t_bar
numerator_one = 0
denominator_one = 0
firstNum_one = one_baffle_time_data[0];
lastNum_one = one_baffle_time_data[len(one_baffle_time_data)-1]
delta_t_one = lastNum_one-firstNum_one
for i in range(one_baffle_time_data.size):
  numerator_one = numerator_one + ((one_baffle_time_data[i])*(one_baffle_concentration_data[i])*delta_t_one)
  denominator_one = denominator_one + ((one_baffle_concentration_data[i])*delta_t_one)
t_bar_one = numerator_one/denominator_one
t_bar_one #(317.4198749169465, 'second')
```    
##### For Two Baffles
```Python
two_baffle_path = 'https://raw.githubusercontent.com/ll643/Lab-5/master/group_3_two_baffle.xls'
two_baffle_firstrow = epa.notes(two_baffle_path).last_valid_index() + 2
two_baffle_time_data = (epa.column_of_time(two_baffle_path,two_baffle_firstrow,-1)).to(u.s)
two_baffle_concentration_data = epa.column_of_data(two_baffle_path,two_baffle_firstrow,1,-1,'mg/L')
two_baffle_concentration_data = two_baffle_concentration_data - two_baffle_concentration_data[0]
two_baffle_V = two_vol
two_baffle_Q = (Q).to(u.m**3/u.s)
two_baffle_theta_hydraulic = (two_baffle_V/two_baffle_Q)
two_baffle_theta_hydraulic #322.2580645161291, 'second'
two_baffle_C_bar_guess = np.max(two_baffle_concentration_data)/2

#use solver to get the CMFR parameters
two_baffle_CMFR = epa.Solver_CMFR_N(two_baffle_time_data, two_baffle_concentration_data, two_baffle_theta_hydraulic, two_baffle_C_bar_guess)
two_baffle_CMFR.C_bar
two_baffle_CMFR.N
two_baffle_CMFR.theta.to(u.s)
two_baffle_CMFR_model = (two_baffle_CMFR.C_bar*epa.E_CMFR_N(two_baffle_time_data/two_baffle_CMFR.theta, two_baffle_CMFR.N)).to(u.mg/u.L)

#AD parameters
two_baffle_AD = epa.Solver_AD_Pe(two_baffle_time_data, two_baffle_concentration_data, two_baffle_theta_hydraulic, two_baffle_C_bar_guess)
two_baffle_AD.C_bar
two_baffle_AD.Pe
two_baffle_AD.theta
two_baffle_AD_model = (two_baffle_AD.C_bar*epa.E_Advective_Dispersion((two_baffle_time_data/two_baffle_AD.theta).to_base_units(), two_baffle_AD.Pe)).to(u.mg/u.L)

#print statements
print('The model estimated mass of tracer injected was',ut.round_sf(two_baffle_AD.C_bar*two_baffle_V ,2) )
print('The model estimate of the Peclet number was', two_baffle_AD.Pe)
print('The tracer residence time was',ut.round_sf(two_baffle_AD.theta ,2))
print('The ratio of tracer to hydraulic residence time was',(two_baffle_AD.theta/two_baffle_theta_hydraulic).magnitude)

#F curve
y_int_2 = integrate.cumtrapz(two_baffle_concentration_data.to(u.mg/u.L), two_baffle_time_data.to(u.s), initial=0)
y_norm_2 = y_int_2/y_int_2.max(axis=0)
plt.plot(two_baffle_time_data.to(u.s), y_norm_2)
plt.xlabel(r'$Time (s)$')
plt.ylabel(r'Concentration Fraction (dimensionless)')
plt.legend(['Measured Dye'])
plt.title('Concentration Fraction vs Time for Two Baffles')
plt.show()

#Finding t* when F = 0.1
t_star_2 = (x_when_y(0.1,one_baffle_time_data,y_norm_2))
t_star_2 #(130.00902623999656, 'second')

#Plot the data and the two model curves.
plt.plot(two_baffle_time_data.to(u.s), two_baffle_concentration_data.to(u.mg/u.L),'r')
plt.plot(two_baffle_time_data.to(u.s), two_baffle_CMFR_model,'b')
plt.plot(two_baffle_time_data.to(u.s), two_baffle_AD_model,'g')
plt.xlabel(r'$Time (s)$')
plt.ylabel(r'Concentration $\left ( \frac{mg}{L} \right )$')
plt.legend(['Measured dye','CMFR Model', 'AD Model'])
plt.title('Concentration vs Time for Two Baffles')
plt.show()

#Calculate t_bar
numerator_two = 0
denominator_two = 0
firstNum_two = two_baffle_time_data[0];
lastNum_two = two_baffle_time_data[len(two_baffle_time_data)-1]
delta_t_two = lastNum_two-firstNum_two
for i in range(two_baffle_time_data.size):
  numerator_two = numerator_two + ((two_baffle_time_data[i])*(two_baffle_concentration_data[i])*delta_t_two)
  denominator_two = denominator_two + ((two_baffle_concentration_data[i])*delta_t_two)
t_bar_two = numerator_two/denominator_two
t_bar_two #236.97432899394502, 'second'
```
##### For Three Baffles
```Python
three_baffle_path = 'https://raw.githubusercontent.com/ll643/Lab-5/master/group_3_three_baffle.xls'
three_baffle_firstrow = epa.notes(three_baffle_path).last_valid_index() + 1
three_baffle_time_data = (epa.column_of_time(three_baffle_path,three_baffle_firstrow,-1)).to(u.s)
three_baffle_concentration_data = epa.column_of_data(three_baffle_path,three_baffle_firstrow,1,-1,'mg/L')
three_baffle_concentration_data = three_baffle_concentration_data - three_baffle_concentration_data[0]
three_baffle_V = three_vol
three_baffle_Q = (Q).to(u.m**3/u.s)
three_baffle_theta_hydraulic = (three_baffle_V/three_baffle_Q)
three_baffle_theta_hydraulic #335.16129032258067, 'second'
three_baffle_C_bar_guess = np.max(three_baffle_concentration_data)/2

#use solver to get the CMFR parameters
three_baffle_CMFR = epa.Solver_CMFR_N(three_baffle_time_data, three_baffle_concentration_data, three_baffle_theta_hydraulic, three_baffle_C_bar_guess)
three_baffle_CMFR.C_bar
three_baffle_CMFR.N
three_baffle_CMFR.theta.to(u.s)
three_baffle_CMFR_model = (three_baffle_CMFR.C_bar*epa.E_CMFR_N(three_baffle_time_data/three_baffle_CMFR.theta, three_baffle_CMFR.N)).to(u.mg/u.L)

#use solver to get the advection dispersion parameters
three_baffle_AD = epa.Solver_AD_Pe(three_baffle_time_data, three_baffle_concentration_data, three_baffle_theta_hydraulic, three_baffle_C_bar_guess)
three_baffle_AD.C_bar
three_baffle_AD.Pe
three_baffle_AD.theta
three_baffle_AD_model = (three_baffle_AD.C_bar*epa.E_Advective_Dispersion((three_baffle_time_data/three_baffle_AD.theta).to_base_units(), three_baffle_AD.Pe)).to(u.mg/u.L)

#print statements
print('The model estimated mass of tracer injected was',ut.round_sf(three_baffle_AD.C_bar*three_baffle_V ,2) )
print('The model estimate of the Peclet number was', three_baffle_AD.Pe)
print('The tracer residence time was',ut.round_sf(three_baffle_AD.theta ,2))
print('The ratio of tracer to hydraulic residence time was',(three_baffle_AD.theta/three_baffle_theta_hydraulic).magnitude)

#Plot the data and the two model curves.
plt.plot(three_baffle_time_data.to(u.s), three_baffle_concentration_data.to(u.mg/u.L),'r')
plt.plot(three_baffle_time_data.to(u.s), three_baffle_CMFR_model,'b')
plt.plot(three_baffle_time_data.to(u.s), three_baffle_AD_model,'g')
plt.xlabel(r'$Time (s)$')
plt.ylabel(r'Concentration $\left ( \frac{mg}{L} \right )$')
plt.legend(['Measured dye','CMFR Model', 'AD Model'])
plt.title('Concentration vs Time for Three Baffles')
plt.show()
```
##### For Three Baffles with Data Trimmed
```Python
three_baffle_path = 'https://raw.githubusercontent.com/ll643/Lab-5/master/group_3_three_baffle_trimmed.xls'
three_baffle_firstrow = epa.notes(three_baffle_path).last_valid_index() + 1
three_baffle_time_data = (epa.column_of_time(three_baffle_path,three_baffle_firstrow,-1)).to(u.s)
three_baffle_concentration_data = epa.column_of_data(three_baffle_path,three_baffle_firstrow,1,-1,'mg/L')
three_baffle_concentration_data = three_baffle_concentration_data - three_baffle_concentration_data[0]
three_baffle_V = three_vol
three_baffle_Q = (Q).to(u.m**3/u.s)
three_baffle_theta_hydraulic = (three_baffle_V/three_baffle_Q)
three_baffle_theta_hydraulic #335.16129032258067, 'second'
three_baffle_C_bar_guess = np.max(three_baffle_concentration_data)/2

#use solver to get the CMFR parameters
three_baffle_CMFR = epa.Solver_CMFR_N(three_baffle_time_data, three_baffle_concentration_data, three_baffle_theta_hydraulic, three_baffle_C_bar_guess)
three_baffle_CMFR.C_bar
three_baffle_CMFR.N
three_baffle_CMFR.theta.to(u.s)
three_baffle_CMFR_model = (three_baffle_CMFR.C_bar*epa.E_CMFR_N(three_baffle_time_data/three_baffle_CMFR.theta, three_baffle_CMFR.N)).to(u.mg/u.L)

#use solver to get the advection dispersion parameters
three_baffle_AD = epa.Solver_AD_Pe(three_baffle_time_data, three_baffle_concentration_data, three_baffle_theta_hydraulic, three_baffle_C_bar_guess)
three_baffle_AD.C_bar
three_baffle_AD.Pe
three_baffle_AD.theta
three_baffle_AD_model = (three_baffle_AD.C_bar*epa.E_Advective_Dispersion((three_baffle_time_data/three_baffle_AD.theta).to_base_units(), three_baffle_AD.Pe)).to(u.mg/u.L)

#print statements
print('The model estimated mass of tracer injected was',ut.round_sf(three_baffle_AD.C_bar*three_baffle_V ,2) )
print('The model estimate of the Peclet number was', three_baffle_AD.Pe)
print('The tracer residence time was',ut.round_sf(three_baffle_AD.theta ,2))
print('The ratio of tracer to hydraulic residence time was',(three_baffle_AD.theta/three_baffle_theta_hydraulic).magnitude)

#F curve
y_int_3 = integrate.cumtrapz(three_baffle_concentration_data.to(u.mg/u.L), three_baffle_time_data.to(u.s), initial=0)
y_norm_3 = y_int_3/y_int_3.max(axis=0)
plt.plot(three_baffle_time_data.to(u.s), y_norm_3)
plt.xlabel(r'$Time (s)$')
plt.ylabel(r'Concentration Fraction (dimensionless)')
plt.legend(['Measured Dye'])
plt.title('Concentration Fraction vs Time for Three Baffles Trimmed')
plt.show()

#Finding t* when F = 0.1
t_star_3 = (x_when_y(0.1,one_baffle_time_data,y_norm_3))
t_star_3 #(125.00483327999099, 'second')

#Plot the data and the two model curves.
plt.plot(three_baffle_time_data.to(u.s), three_baffle_concentration_data.to(u.mg/u.L),'r')
plt.plot(three_baffle_time_data.to(u.s), three_baffle_CMFR_model,'b')
plt.plot(three_baffle_time_data.to(u.s), three_baffle_AD_model,'g')
plt.xlabel(r'$Time (s)$')
plt.ylabel(r'Concentration $\left ( \frac{mg}{L} \right )$')
plt.legend(['Measured dye','CMFR Model', 'AD Model'])
plt.title('Concentration vs Time for Three Baffles Trimmed')
plt.show()

#Calculate t_bar
numerator_three = 0
denominator_three = 0
firstNum_three = three_baffle_time_data[0];
lastNum_three = three_baffle_time_data[len(three_baffle_time_data)-1]
delta_t_three = lastNum_three-firstNum_three
for i in range(three_baffle_time_data.size):
  numerator_three = numerator_three + ((three_baffle_time_data[i])*(three_baffle_concentration_data[i])*delta_t_three)
  denominator_three = denominator_three + ((three_baffle_concentration_data[i])*delta_t_three)
t_bar_three = numerator_three/denominator_three
t_bar_three #236.97836398996662, 'second'
```
