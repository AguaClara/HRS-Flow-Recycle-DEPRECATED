# High Rate Sedimentation: Flow Recycle, Fall 2018
#### Justin Conneely and Leena Sen

#### October 26th, 2018

## Abstract
Previous High Rate Sedimentation (HRS) teams have observed that at higher upflow velocities, the floc blanket is much more dense at the top of the recirculator than at the bottom. Because of this, they have hypothesized that installing a recycle line from the top of the recirculator to the bottom of the recirculator will improve floc blanket longevity and increase overall reactor performance. The Fall 2018 team has run a baseline experiments, and has begun to fabricate the flow recycle system. In the future, the team will test the recycle system at varying angles of entry into the recirculator and at various upflow velocities. [Very clear abstract! Explains what the goal is and why the team exists!]

## Introduction
Sedimentation is the process by which coagulated contaminant particles are removed from water via gravitational settling. In a sedimentation tank, water flows upward as the flocs settle downward. Those flocs settle into a "floc blanket" at the bottom of the sedimentation tank. A floc blanket is a fluidized bed of suspended solids with a high rate of collisions. The particles in the floc blanket collide with coagulant particles and other flocs, coming together to form heavier flocs that settle to the basin of the recirculator, which still remains as part of the floc blanket. This process cleans the water, resulting in a lower effluent NTU (Nephelometric Turbidity Unit, a measure of clarity).

In the AguaClara lab, the sedimentation tank's plate settlers are simulated by section of plastic PVC piping called the tube settler. The section of tube where the floc blanket forms is referred to as the "recirculator" by the HRS teams. Since the behavior of a section of fluid is representative of the entire tank, tubing can be used to simulate a simple pathway in the reactor. This allows for a practical method of experimentation on a smaller scale. See figure 1 for a visual comparison of the sedimentation tank in an AguaClara plant to the sedimentation tank in lab.


![SedTank](https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Lab%20vs%20Plant%20Sed%20Tanks.JPG?raw=true)

Figure 1: Comparison of a sedimentation tank in an AguaClara plant and a sedimentation tank in the AguaClara lab.

The HRS teams aim to design a tank that will yield an effluent of no more than 0.3 NTU while maintaining high upflow velocity. Operating at a higher upflow velocity will allow for greater water processing in a given period of time, which will decrease plant operating costs. However, when operating at a high upflow velocity in lab, the floc blanket is unstable. The floc blanket is dense near the top of the recirculator, but very thin near the bottom. HRS: Flow Recycle hopes to remediate this issue by installing a recycle line. This will allow future teams to continue researching the potential viability of high upflow velocities in AguaClara plants.

## Literature Review and Previous Work
Several past researchers have studied the process of sedimentation and the properties floc blankets. Their research gives valuable insight to the Fall 2018 HRS: Flow Recycle Team's results. Culp et al. (1968) research different angles to find the optimal slope of the tube settlers. Using normal laboratory conditions, a 60 degree angle with respect to the horizontal provided continuous sludge removal while showing effective sedimentation performance. This information was used by the Fall 2017 team when designing the tube settler that is currently being used.

Hurst (2010) noted that the presence of the floc blanket enhanced the removal of particles. Their experiments found that upflow velocities of 1.0 to 1.3 mm/s produced the best performance. Past HRS teams have been successful at establishing floc blankets at higher velocities than the range given by Hurst (3 mm/s), but those floc blankets were not stable.

Swetland (2014) discovered that as larger flocs formed in the sedimentation tank, those flocs would settle due to their high density relative to the fluid. Additionally, they discovered that in order for particle removal to occur, flocs need to have a higher settling velocity than the capture velocity. As the flocs concentrate and fall to the bottom of the sedimentation tank, a floc blanket forms. These findings informed the High Rate Sedimentation teams' understanding of floc formation.

In a similar vein, Balwan (2016) explored how the length of the tube settlers effected effluent turbidity. He found that increasing the length of tube settler increased the amount of particles removed by the reactor. With tube settlers at an angle of 45 degrees and 60 cm length, turbidity removal was measured to be 80 percent. However, his experiments only had three length variables (40cm, 50cm, 60cm) and the effluent of longer tube settlers were unknown.

The Summer 2018 Team observed that at higher upflow velocities, the floc blanket was much more dense at the top of the recirculator than at the bottom. They proposed that the Fall 2018 team design a recycle line to allow for flocs at the top of the recirculator to flow back to the bottom and re-establish a more uniform distribution. This observation is what motivated the goal of the current team, which is to design that recycle line and test the new apparatus.


## Methods

### Experimental Apparatus
The set-up of the Flow Recycle Subteam's lab bench consists of several parts (Figure 2). These parts include the three different pumps, the clay and coagulant stocks, the flocculator, the sedimentation tank (and recycle line), and the influent and effluent turbidimeters.

<img src="https://raw.githubusercontent.com/JustinConneely/Personal/master/Images/Lab%20Bench%20Setup.png" height250 width=400>

Figure 2: This is a photograph highlighting the pumps, stocks, and turbidimeters in the lab bench set-up.

This system allows the team to model the water treatment process in a lab setting. The influent and effluent turbidimeters record the turbidity of the water entering and leaving the system. In order to run experiments, tap water is mixed with clay water. This is referred to as the influent. The influent is maintained at a constant turbidity of 100 NTU through ProCoDA's PID dosing control.

After exiting the influent turbidimeter, the water enters the flocculator. Upon entering the flocculator, the water is dosed with the coagulant polyaluminum chloride (PAC). The coagulant pump controls how much of the coagulant stock enters the system. After choosing the desired dosage, the team uses a python markdown file to determine the ideal stock concentration. In conjunction with this, the markdown file returns the required coagulant pump RPM that goes with the desired stock concentration. Once the coagulant is added, the water then passes through the flocculator, which allows for the formation of flocs. Next, the flow  enters the bottom of the sedimentation tank. The effluent that exits through the top of the tube settler then flows through the effluent turbidimeter in order to find the turbidity of the effluent. After exiting  the effluent turbidimeter, the water then flows to the wasteline.

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

Where d is the diameter of the pipe, g the gravity force, v is viscosity and ρ represents the different densities of the water and the floc.

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
n/a (in progress)

## Conclusions
n/a (in progress)

## Future Work
n/a (in progress)

## Bibliography
Balwan, K. (2016). Study of the effect of length and inclination of tube settler on the effluent quality. Journal (International Journal of Innovative Research and Advanced Engineering).

Culp, G., Hansen, S., & Richardson, G. (1968). High-rate sedimentation in water treatment works. Journal (High-Rate Sedimentaion in Water Treatment Works).

Galantino, C., Oritz, A., & Zarecor, M. (2017). High Rate Sedimentation Fall 2017 Report.

Hong, A., Si, H. (2018). High Rate Sedimentation Summer 2018 Report.

Hurst, M. (2010). Evaluation Of Parameters Affecting Steady-State Floc Blanket Performance. Thesis (Cornell University).

Swetland, K., Weber-Shirk, M., Lion, L. (2014). Flocculation-sedimentation performance model for laminar flow hydraulic flocculation with polyaluminum chloride and aluminum sulfate coagulants. Journal (Journal of Environmental Engineering).

Zarecor, M., Sharma, S., Conneely, J. (2018). High Rate Sedimentation Spring 2018 Report.

## Manual

n/a (in progress)
