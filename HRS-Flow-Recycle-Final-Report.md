# High Rate Sedimentation: Flow Recycle, Fall 2018
#### Justin Conneely and Leena Sen
#### November 29th, 2018

## Abstract
Previous High Rate Sedimentation (HRS) teams have observed that at higher upflow velocities, the floc blanket is denser at the top of the recirculator than at the bottom. Given these results, they hypothesized that installing a recycle line from the top of the recirculator to the bottom of the recirculator will improve floc blanket longevity and increase overall reactor performance. The Fall 2018 team has run baseline experiments, fabricated the flow recycle system, and tested various methods to reverse flow.

## Introduction
Sedimentation is the process by which coagulated contaminant particles are removed from water via gravitational settling. In a sedimentation tank, water flows upward as flocs settle downward. Those flocs settle into a "floc blanket" at the bottom of the sedimentation tank. A floc blanket is a fluidized bed of suspended solids with a high rate of collisions. The particles in the floc blanket collide with coagulant particles and other flocs, coming together to form heavier flocs that settle to the basin of the recirculator. These heavier flocs remain in the reactor as part of the floc blanket. This process cleans the water, resulting in a lower effluent NTU (Nephelometric Turbidity Unit, a measure of clarity).

In the AguaClara lab sedimentation tank setup, a section of PVC piping known as the "tube settler" simulates a life-size sedimentation tank's plate settlers. The section of tube where the floc blanket forms is referred to as the "recirculator" by the HRS teams. Since the behavior of a section of fluid is representative of the entire tank, tubing can be used to simulate a simple pathway in the reactor. This allows for a practical method of experimentation on a smaller scale. Refer to Figure 1 for a visual comparison of the sedimentation tank in an AguaClara plant to the sedimentation tank in the lab.


![SedTank](https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Lab%20vs%20Plant%20Sed%20Tanks.JPG?raw=true)

Figure 1: Comparison of a sedimentation tank in an AguaClara plant and a sedimentation tank in the AguaClara lab.

The HRS teams aim to design a tank that will yield an effluent of no more than 0.3 NTU while maintaining high upflow velocity. Upflow velocity is the speed at which the particles travel upward through the sedimentation tank. Similarly, the capture velocity is the highest possible settling velocity of a particle that the tube settling will catch. Operating at a higher upflow velocity will allow for greater water processing in a given period of time, which will decrease plant operating costs. However, when operating at a high upflow velocity in lab, the floc blanket is unstable. The floc blanket is dense near the top of the recirculator, but very thin near the bottom. HRS: Flow Recycle hopes to remediate this issue by installing a recycle line. This will allow future teams to continue researching the potential viability of high upflow velocities in AguaClara plants.

## Literature Review and Previous Work
Several past researchers have studied the process of sedimentation and the properties floc blankets. Their research gives valuable insight to the Fall 2018 HRS: Flow Recycle Team's results. Culp et al. (1968) researched different angles to find the optimal slope of the tube settlers. Using normal laboratory conditions, a 60 degree angle with respect to the horizontal provided continuous sludge removal while showing effective sedimentation performance. This information was used by the Fall 2017 team when designing the tube settler that is currently being used.

Hurst (2010) noted that the presence of the floc blanket enhanced the removal of particles. Their experiments found that upflow velocities of 1.0 to 1.3 mm/s produced the best performance. Past HRS teams have been successful at establishing floc blankets at higher velocities than the range given by Hurst (3 mm/s), but those floc blankets were not stable.

Swetland (2014) discovered that as larger flocs formed in the sedimentation tank, those flocs settled due to a higher density relative to the fluid. Additionally, they discovered that in order for particle removal to occur, flocs need to have a higher settling velocity than the capture velocity. As the flocs concentrate and fall to the bottom of the sedimentation tank, a floc blanket forms. These findings informed the High Rate Sedimentation teams' understanding of floc formation.

In a similar vein, Balwan (2016) explored how the length of the tube settlers effected effluent turbidity. He found that increasing the length of tube settler increased the amount of particles removed by the reactor. With tube settlers at an angle of 45 degrees and 60 cm length, turbidity removal was measured to be 80 percent. However, his experiments only had three length variables (40cm, 50cm, 60cm) and the effluent of longer tube settlers were unknown.

The Summer 2018 Team observed that at higher upflow velocities, the floc blanket was much more dense at the top of the recirculator than at the bottom. They proposed that the Fall 2018 team design a recycle line to allow for flocs at the top of the recirculator to flow back to the bottom and re-establish a more uniform distribution. This observation is what motivated the goal of the current team, which is to design that recycle line and test the new apparatus.


## Methods

### Experimental Apparatus
The set-up of the Flow Recycle Subteam's lab bench consists of several parts (Figure 2). These parts include the three different pumps, the clay and coagulant stocks, the flocculator, the sedimentation tank (and recycle line), and the influent and effluent turbidimeters.

<img src="https://raw.githubusercontent.com/JustinConneely/Personal/master/Images/Lab%20Bench%20Setup.png" height250 width=400>

Figure 2: This is a photograph highlighting the pumps, stocks, and turbidimeters in the lab bench set-up.

This system allows the team to model the water treatment process in a lab setting. The influent and effluent turbidimeters record the turbidity of the water entering and leaving the system. In order to run experiments, tap water is mixed with clay water. This is referred to as the influent. The influent is maintained at a constant turbidity of 100 NTU through ProCoDA's PID dosing control.

After exiting the influent turbidimeter, the water enters the flocculator. Upon entering the flocculator, the water is dosed with the coagulant polyaluminum chloride (PACl). The coagulant pump controls how much of the coagulant stock enters the system. After choosing the desired dosage, the team uses a Python markdown file to determine the ideal stock concentration. In conjunction with this, the markdown file returns the required coagulant pump RPM that goes with the desired stock concentration. Once the coagulant is added, the water then passes through the flocculator, which allows for the formation of flocs. Next, the flow  enters the bottom of the sedimentation tank. The effluent that exits through the top of the tube settler then flows through the effluent turbidimeter in order to find the turbidity of the effluent. After exiting the effluent turbidimeter, the water then flows to the wasteline.

Almost all particle removal subteams use HRS standard apparatus design in conjunction with a the traditional flocculator designed by the High G Flocculation Fall 2017 team. The flocculator in lab mimics the process in an actual AguaClara plant by attaining a sufficient collision potential (G). Values for the different parameters of the flocculator are listed in the following table.

Table 1: Below are the parameters and values of the current flocculator design.

| Parameter | Meaning | Value |
| ----- | ------------------------ | ----- |
| V.Sed | Sed Tank Upflow Velocity | 3 mm/s |
| D.Sed | Sed Tank Inner Diameter  | 1 in  |
|Q.Sed, Q.Reactor| Flow rate (from V.Sed) |1.52 mL/s|
|D.Floctube|Floctube Inner Diameter| 0.17 in |
|R.c|Radius of Curvature of Floc Coils|5 gm|
| Gtheta | G*theta | 20,000 |
|  G  |  Shear   |  175.5 Hz  |
|Theta |Residence Time | 1.899 min or 113.9 s|
| L.Flocc| Length of Flocculator Tubing|11.821 m|
|Epsilon.Flocc |Energy Dissipation Rate| 30.814 mW/kg|

### The Standard Design
This section contains the details behind the Fall 2017 HRS Team's "Standard Design" of the sedimentation tank.

The geometry of the standard design is centered around the concept of capture velocity. Capture velocity is defined as the speed of the slowest moving particle that the reactor can capture. Similarly, the terminal settling velocity is reached when the viscous shear of the fluid and the buoyant force balance with the gravity. The relationship between particle diameter and terminal settling velocity is shown in Stoke’s Theorem:

$$ V_t = \frac{d^2g}{18v} * \frac{ρ_{floc} - ρ_{H_2O}}{ρ_{H_2O}} ... (2)$$

Where d is the diameter of the pipe, g is the gravity force, v is viscosity and ρ represents the different densities of the water and the floc.

The capture velocity depends on several different properties of the sedimentation tank being used, as one can see in the following formula:

$$ V_c = \frac{SV_αsinα}{Lsinαcosα+S} ... (3)$$

Where α is the angle of the tube settler, V<sub>α</sub> is the upflow velocity, L is the length of the tube settler (after the floc weir), and S is the diameter of the tubing.

If a floc has a terminal settling velocity that is too low, it will not be captured and instead will escape with the effluent. The distance after the floc weir is used as the active length of the tube settler in the capture velocity calculation. With an active length of 27.08 cm, the  capture velocity of the standard design is 0.462 mm/s. For consistence across research teams, the tube settler is at a 60<sup>o</sup> angle relative to the horizontal axis. Additionally, the inner diameter of the reactor is 1 inch so as to improve visibility during experimentation.

### Procedure

#### Experiment One
The aforementioned setup was used to test the effect of introducing a recycle line on floc blanket degradation and effluent turbidity. This was tested first by flushing the system to assure that all coagulant and clay particles were taken out of the system, and then stabilizing influent turbidity at 100 NTU by dosing clay using the PID control in ProCoDa. The HRS Flow Recycle Team tested the system first without a recycle line. This experiment was conducted with a coagulant dosage of 4.2 mg/L, which is the optimal dose as determined by the HRS Spring 2018 Team. Additionally, a constant upflow velocity of 3 mm/s is used(experimentally extrapolated from an RPM of 28.3). Under these same conditions, the effectiveness of a recycle line in increasing longevity of the floc blanket was tested. A recycle line was incorporated into the sedimentation tank by drilling beneath the floc weir and above the elbow created by the floc weir and tube settler, as shown in figure 3.

![RecycleLine](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/RecycleLine.jpeg)
Figure 3: This is a photograph of the aforementioned recycle line.

Quarter-inch diameter PVC tubing was installed to connect from this location to the bottom of the tube settler after drilling and tapping to create a water-tight seal. Clay and coagulant were then dosed as previously stated, and data from the total ~20 hour experiment included recordings on influent and effluent turbidity, head loss across the flocculator, and the time at with each of the data points were recorded.

## Results and Analysis

### Experiment One
After installation of the recycle line, reactor performance decreased; the effluent turbidity was consistently ~30 NTU higher than the baseline trial for the duration of the test, as is shown in figure 4. It was observed that instead of water flowing back down the recycle line, it instead traveled up both the recirculator and the recycle line in parallel.

![ExperimentOne](https://user-images.githubusercontent.com/36204276/47260870-85817380-d491-11e8-8b86-a56ee3dd6943.PNG)
Figure 4: This figure displays the effluent turbidity of the reactor both with and without flow recycle implemented.

### Experiment Two
Next, a series of experiments was conducted with the recycle line closed for the initial portion of the experiment so that the floc blanket would have time to establish itself before introducing a new factor. It was hypothesized that doing this would reverse the direction of flow, but this yielded similar results to experiment one.

![ExperimentTwo](https://user-images.githubusercontent.com/36204276/48650719-5b09d400-e9c5-11e8-80e2-6b86610b714e.png)
Figure 5: This is a graph displaying effluent turbidity with flow recycle.

As you can see above in figure 5, the effluent was relatively with the baseline until the recycle line valve was opened at about three hours in, at which point the effluent increased by roughly 15 NTU.  

### Experiment Three
With consistently poor results, the subteam then hypothesized that the design of the tap at the top of the recycle line was a potential factor affecting these results. To mitigate this, a new tap was installed that was flush with the inside of the tube settler in order to prevent floc buildup, as is shown in figure 6.

![NotFlushTap](https://user-images.githubusercontent.com/36204276/48650176-2b59cc80-e9c3-11e8-9669-974f09f35f40.jpg)
Figure 6: This photograph shows floc buildup on the top of the tap as a result of it not being flush with the tube settler's inner diameter.

This experiment yielded results that were strikingly similar to the results of our baseline trial without flow recycle. It was also observed that the floc blanket collapsed more quickly than in experiments one and two, prior to the opening of the recycle line at ~5.5 hours into the experiment. These results can be seen below in figure 7.

![NotFlushTap](https://user-images.githubusercontent.com/36204276/49189431-5554ac80-f33c-11e8-9840-02de6af5ba9f.PNG)

Figure 7: This graph compares reactor performance with the tap flush to the recirculator inner diameter to the baseline test without flow recycle. The valve was opened for the recycle line trial at approximately 5.5 hours in.

## Conclusions
Based on the above data, the HRS team is unable to conclude whether the recycle line will actually help the longevity of the floc blanket. Results thus far have not been promising, but different approaches and tests are ongoing. The team believes that adjusting the entrance of the tap itself and that incorporating a peristaltic pump to reverse water flow in the favored direction to increase floc blanket longevity could also make the recycle line effective.

Experiment 1 involved the installation of a recycle line. This resulted in decreased reactor performance, as the effluent turbidity resulted in a consistent ~30 NTU increase versus the baseline trial throughout the test. Furthermore, water tended to flow up both the recirculator and recycle line rather than down the recycle line, opposing the movement of water along the recirculator.

Experiment 2 demonstrated that performing the test with the recycle line closed for the initial portion of the experiment yielded the same results as Experiment 1 despite hopes that doing so would allow for the direction of flow to be reversed.

Experiment 3 involved a new approach; the design of the tap at the top of the recycle line was taken into consideration and a new one was installed such that the tap was flush with the inside of the tube settler. This experiment yielded results that were strikingly similar to our baseline trial; this leads us to believe that the bottom geometry of the reactor may be inhibiting the effectiveness of the recycle line.

## Future Work
Future directions for Flow Recycle include incorporating a peristaltic pump along the recycle line to force water in the direction opposing flow along the recirculator to help increase floc blanket longevity. Incorporation of the peristaltic pump would correct direction of flow in the recycle line. This could serve as proof of concept if it improves reactor performance, and future HRS subteams could then work to develop a method of correcting flow without the use of a pump.

Other options include working with HRS Bottom Geometry to help design a new geometry of the bottom of the sedimentation tank. Fixing this issue could potentially allow for more investigation into the potential effectiveness of flow recycle.

## Bibliography
Balwan, K. (2016). Study of the effect of length and inclination of tube settler on the effluent quality. Journal (International Journal of Innovative Research and Advanced Engineering).

Culp, G., Hansen, S., & Richardson, G. (1968). High-rate sedimentation in water treatment works. Journal (High-Rate Sedimentaion in Water Treatment Works).

Galantino, C., Oritz, A., & Zarecor, M. (2017). High Rate Sedimentation Fall 2017 Report.

Hong, A., Si, H. (2018). High Rate Sedimentation Summer 2018 Report.

Hurst, M. (2010). Evaluation Of Parameters Affecting Steady-State Floc Blanket Performance. Thesis (Cornell University).

Swetland, K., Weber-Shirk, M., Lion, L. (2014). Flocculation-sedimentation performance model for laminar flow hydraulic flocculation with polyaluminum chloride and aluminum sulfate coagulants. Journal (Journal of Environmental Engineering).

Zarecor, M., Sharma, S., Conneely, J. (2018). High Rate Sedimentation Spring 2018 Report.

## Manual
### Experimental Methods
#### Set-up
1. Back-flush flocculator and sed tank to remove and residual particles from prior experiments.

2. Clean the influent and effluent turbidimeters to make sure turbidity readings are accurate.

3. Make the clay stock by adding a little bit of clay  to the reservoir and filling it with tap water

4. Make the coagulant stock by filling the reservoir with 5 L of DI water. Use PACl Dosing python file to determine required PACl dose and add it to the reservoir.

5. Run water through the system to fill sedimentation tank and to let all the air exit the system.

6. Dose clay until influent stabilizes at 100 NTU, making sure to open the flocculator and sed tank bypass line so that clay isn't being dosed through the entire system.

7. Start dosing coagulant and begin the experiment, making sure to start logging data in ProCoDa.

(Pre- and post-experiment checklists can be found in more detail on [the subteam's wiki page.](https://github.com/AguaClara/HRS-Flow-Recycle/wiki/Pre-Experiment-and-Post-Experiment-Checklists))

### ProCoDA Method File

The following is taken directly from the Calibrating PID Control on the [AguaClara Confluence website](https://confluence.cornell.edu/display/AGUACLARA/Calibrating+PID+Control):

> To establish constants for PID control in ProCoDA, follow the procedure summarized below:

> 1. After you have loaded the proper PID control function and have created the appropriate set points in your method file, set the P, I, and D set points to zero.
> 2. Set P to a small value and change the target value to provoke a response from the PID control
> 3. Observe the graph of the variable being controlled for this value of P. If the result is an oscillation that becomes damped (decreasing amplitude), increase the value of P incrementally and repeat the process. If the result is an oscillation that becomes amplified (increasing amplitude), lower the value of P and repeat the process.
> 4. The objective is to find a value of P for which there is a periodic oscillation of the value with a constant amplitude. Once the correct P value (Ku) has been found, write it down and also record the period of the wave (time between two consecutive crests of the oscillation - Pu - in minutes).
> 5. AguaClara researchers typically use PI control (the value of D is set to zero). To find the value of P required, use the equation: P = Ku/2.2. To find the value of I required, use the equation: I = Pu/1.2. This should result in a value in minutes, which is the correct unit for I.
> 6. Change your set points (P and I) to the new values. Ensure that there is less than 10 percent variation in your variable, and fine tune if necessary.

> This calibration method may result in oscillatory behavior. To reduce variability in the output, consider reducing P to damp the oscillations. This will reduce the responsiveness of the algorithm and will increase the stability.

#### States
In order to properly begin an experiment, the ProCoDA method file must be set to the "ON" state. When an experiments in not in progress, ProCoDA should be turned to the "OFF" state.
* ON: The active state of ProCoDa. The 1 rpm pump drain is turned on (for draining the floc hopper) and the the clay pump control (with PID) is turned on.

* OFF: Resting state of ProCoDA. All sensors, relays, and pumps are turned off.

<p align="center">
  <img src="/Images/ProCoDA/On State.png" width=600>
</p>

Figure 8: The ON state of the HRS: Flow Recycle ProCoDA method file.

#### Set Points
The following is an exhaustive list of all the Set Points in the method file and their corresponding values. Exact location of these points in the method file can be seen figure XX below.

<p align="center">
  <img src="/Images/ProCoDA/Set Points.png" width=600>
</p>

Figure 9: This is the overall order of the Set Points for the HRS method file.


* OFF: constant that has no units and value of 0
* ON: constant that has no unitsand a value of 1
* Turb Target: constant with a value of 100 NTU; represents the desired influent turbidity
* P: constant with a value of 300m determined through method mentioned in "PID Control" section of report
* i: constant with no units and a value of 2.3 as determined through method mentioned in "PID Control" section of report
* D: constant with no units and a value of 0

<p align="center">
  <img src="/Images/ProCoDA/Output Settings.png" width=600>
</p>

Figure 10: These are the output settings for the PID state. This process runs in the background and only needs to be set up at the beginning of the semester.

* Influent Turbidimeter ID: constant with no units that has a value of 1; this value is due to the step in which the turbidimeter is installed and acknowledged in the data recording process
* Influent Turbidity:  varaible with no units and a value of 0

<p align="center">
  <img src="/Images/ProCoDA/Influent Set Point.png" width=600>
</p>

Figure 11: This shows the influent turbidity Set Point and the selected sensors required in order to establish this relationship.

* Effluent Turbidimeter ID: constant with no units and a value of 2; Effluent Turbidimeter ID is 2 since it takes in data in the system than the Influent Turbidimeter ID
* Effluent Turbidity: varaible with no units and a value of 2
* PumpControl(Clay): variable with no units and a value of 0

<p align="center">
  <img src="/Images/ProCoDA/Pump Control.png" width=600>
</p>

Figure 16: This depicts the relationship between the PumpControl(Clay) variable and the set points P, i, D, and Influent Turbidity.

### Python Code
#### Variables

$C_{sys}$: Concentration of coagulant in system

$C_{labstock}$: Concentration of coagulant in lab stock

$Q_{sys}$: Flow rate of system

$K_{dilution}$: Dilution factor in reservoir

$V_{reservoir}$: Volume of reservoir

$Frac_{resivor}$: Fraction of usable reservoir

$Q_{per rpm}$: Flow rate per pump rpm

$M_{flowcoag}$: Mass flow rate of coagulant

$C_{reservoir}$: Concentration of coagulant in reservoir

$Q_{reservoir}$: Flow rate out of reservoir

$RPM$: pump RPM required for desired flow rate

$RunTime$: Amount of time the experiment can run without the coagulant reservoir emptying

#### Python Code

```python
from aide_design.play import*

#inputs
C_sys = 4.2*(u.mg/u.L)
C_labstock = 70.28*(u.g/u.L)   #be sure to verify
Q_sys = 1.48*(u.mL/u.s)
K_dilution = 1.42*(u.mL/u.L)
V_reservoir = 5*(u.L)
Frac_reservoir = .76
Q_per_rpm = .001828 *(u.mL/u.s)

#Calculations
M_flow_coag = (Q_sys * C_sys).to(u.mg/u.s)
C_reservoir = (C_labstock * K_dilution).to(u.gram/u.L)
Q_reservoir = (M_flow_coag / C_reservoir).to(u.mL/u.s)

#Outputs
RPM = Q_reservoir / Q_per_rpm
RunTime = ((V_reservoir * Frac_reservoir) / Q_reservoir).to(u.hour)
Total_coag = (K_dilution * V_reservoir)

print('The RPM needed for this coagulant dosage is' ,RPM)
print('The run time is ', RunTime)
print('The total coagulant needed is ', Total_coag)
```
