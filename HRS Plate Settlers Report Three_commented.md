# High Rate Sedimentation: Plate Settlers, Spring 2019
#### Leena Sen, Carmen Ortega, Luke Meyer
#### March 16th, 2019

**[Felix here grading. Same thing as last time. After addressing any comments please write within the brackets "-Addressed __" with the individual's initials in the __ space. They will be deleted in the next report, unless it is a comment approving of what you have done. In that case delete it yourself.]**

## Abstract
Previous High Rate Sedimentation (HRS) teams observed floc blankets are denser at the top than at the bottom, which causes tears in the blanket at high upflow velocities. By improving floc blanket longevity, the speed of the sedimentation tank can be efficiently increased. The Spring 2019 team reconstructed a model of a sedimentation tank, as to enable targeted testing of this issue using plate settlers. While plates have been proven as helpful for AguaClara designs, HRS fabricated a plate-testing device to allow modifications of plate-settler variables in the model. The design enables for alterations of the plate-angle ranging from 30-60&deg; and a removal/addition system to control channel-width. While no ~~component~~ **[variable]** variable-experimentation [-Addressed LM] occurred, theory predicts angle-modifications to be the more impactful of the two variables. [-Addressed (too long of abstract) LM]

**[Lit review and previous work should be right after abstract]** [because this is now placed immediately after the abstract, we defined some terms in here rather than elsewhere. let us know if this is incorrect procedure.]**[Oh this is really unfortunate. I don't know why I said that lit review and previous work should be right after abstract. I mean to say right after introduction... Sorry about this!]**[-Addressed LM]

## Introduction
Sedimentation is the process by which coagulated contaminant particles are removed from water via gravitational settling. In a sedimentation tank, water flows upward as flocs, the coagulated fragments, settle downward. Those flocs settle into a "floc blanket" at the bottom of the sedimentation tank. A floc blanket is a fluidized bed of suspended solids that has a high rate of collisions. The particles in the floc blanket collide with coagulant particles and other flocs, coming together to form heavier flocs that settle to the basin of the recirculator. These heavier flocs remain in the reactor as part of the floc blanket. This process cleans the water, resulting in a lower effluent NTU (Nephelometric Turbidity Unit, a measure of clarity). The lower the outgoing, or "effluent" turbidity, the cleaner the water is.

In the AguaClara sedimentation tank setup, a section of PVC piping known as the "tube settlers" simulates a life-size sedimentation tank's plate settlers. Multiple other tubing systems model the floc hopper and floc weir, as well as the inlet jet tube and influent and effluent lines that carry water in and out of the system. Since the behavior of a section of fluid is representative of the entire tank, tubing can be used to simulate a simple pathway in the reactor. This allows for a practical method of experimentation on a smaller scale. Refer to Figure 1 for a cross-sectional view of the sedimentation tank in an AguaClara plant to the sedimentation tank, and to Figure 2 for a visual representation of the model used by the HRS: Plate Settlers team.

![SedTank](https://github.com/CarmenOrtega/aguaclara_tutorial/blob/master/ACSedTank.PNG?raw=true)

Figure 1. Design schematic of the sedimentation tank in the AguaClara plants.

![SedTankDiagram](https://github.com/CarmenOrtega/aguaclara_tutorial/blob/master/SedTankDiagram.PNG?raw=true)

Figure 2. Design schematic of experimental apparatus. Influent enters the sedimentation tank from the flocculator via inlet jet tubes of variable size. Downward direction of the influent flow is redirected upward by the semicircular jet reverser bottom geometry..

The HRS team aims to design a tank that will yield an effluent turbidity of no more than 0.3 NTU while maintaining high upflow velocity. Operating at a higher upflow velocity will allow for a greater volume of water processing in a given period of time, which will decrease plant operating costs. However, when operating at a high upflow velocity in lab, the floc blanket is unstable. The blanket is dense near the top of the recirculator, but very thin near the bottom. HRS: Plate Settlers plans to remediate this issue by incorporating a second set of plate settlers within the sedimentation tank itself. As more particles enter through the manifold, flocs at the top of the blanket overflow into the floc hopper or floc weir. The smallest particles which make it past the floc blanket and floc hopper then enter the plate settlers. Plate settlers catch the smallest particles by increasing the horizontal space where particles can settle out. Plate settler length, channel-width (how far apart each plate is from its neighbor), and angle from the horizon determines capture velocity.

In order to ensure floc blanket stability, the team proposes 45&deg; to be the ideal plate-angle. This is operating under the hypothesis that plate settlers follow the principles that govern particle capture in a tube settler. Henceforth, based on the Figre 3, angle \alpha A is 45&deg;, because this maximizes the distance the floc travels, and that enables an even distribution and long creation of the floc blanket. [-Addressed LM, Kanha said to include hypothesis in introduction]

![longest_path](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/longest_path.png)

Figure 3. Longest possible path of a floc through a sedimentation tube

By increasing the number of plate settlers, and thereby the area in which the flocs can settle, HRS: Plate Settlers intends to increase the capture velocity and therefore achieve a more stabilized floc blanket. In order to test this, a proper model-tank and experimentation system must first be developed. If successful, this will allow future teams to continue researching the potential viability of high upflow velocities in AguaClara plants. Furthermore, progress in the context of plate settlers held significance in two ways: a major improvement for High Rate Sedimentation as a subteam and for the process of flocculation in the overall water treatment process. Such advances would achieve a long-term goal of improving floc blanket stability (and thus improve the entire particle removal process) at both a model and real-life scale.

## Literature Review and Previous Work
Several past researchers have studied the process of sedimentation and the properties of floc blankets. Their research gives valuable insight to the Spring 2019 High Rate Sedimentation AguaClara team.

Culp et al. (1968) researched different angles to find the optimal slope of tube settlers: tubing that forces loose-flocs back into the sedimentation tank. Using normal laboratory conditions, a 60 degree angle with respect to the horizontal provided continuous sludge removal while showing effective sedimentation performance. This gave the team a maximum angle to test plate settlers with.

Furthermore, Hurst (2010) noted that the presence of the floc blanket enhanced the removal of particles. Their experiments found that upflow velocities of 1.0 to 1.3 mm/s produced the best performance. Past HRS teams have been successful at establishing floc blankets at higher velocities than the range given by Hurst, up to 15 mm/s, but those floc blankets were not stable; therefore, in order to ensure stability the team will use the velocities aforementioned by Hurst. A longer definition of the floc blanket and its purpose can be found in the introduction. **[As I said above intro should be above previous work/lit review. Again sorry about that.]** [-Addressed LM]

In regards to controlling a blanket effectively, Swetland (2014) discovered that as larger flocs formed in the sedimentation tank, those flocs would settle due to their high density relative to the fluid. Additionally, they found that in order for particle removal to occur, flocs need to have a higher settling velocity than the capture velocity. The capture velocity is the lowest velocity at which plates can catch particles, while the settling velocity is the optimal and averaged speed for flocs to descend at. As the flocs concentrate and fall to the bottom of the sedimentation tank, a floc blanket forms. **[Again you can define it in intro now that it will be above prev work+lit review]** [-Addressed LM (Kanha's comment regarding defining floc blanket prior to this has now also been addressed as well)] These findings informed the High Rate Sedimentation teams' understanding of floc formation, so that they could designed a plate geometry that accommodates this settling and formation.

In a similar vein, Balwan (2016) explored how the length of the tube settlers affected effluent turbidity. He found that increasing the length of tube settler increased the amount of particles removed by the reactor. With tube settlers at an angle of 45 degrees and 60 cm length, turbidity removal was measured to be 80 percent. However, his experiments only had three length variables (40cm, 50cm, 60cm) and the effluent of longer tube settlers were unknown. As a result, the initial design for the plate settlers had plastic at a 45 degree angle. The angle is crucial in determining the effectivity of the plate settler in increasing upflow while decreasing turbidity. This is due to the proportional interaction that channel geometry has with the velocity gradient.

Hurst (2016) derived that rather than just increasing the upflow velocity to increase the creation of the floc blankets, alum dosage must also be considered. The turbidity and upflow velocity work in tandem to determine the stability of a suspended floc blanket. In the experiments described in Hurst (2016), upflow velocity was held constant at 1.2 mm/s, but coagulant doses (ranging from 1.0 to 7.5 mg/L) were varied in 10 nephelometric turbidity units between 100 NTU and 500 NTU. That being said, 15 mg/L of alum was found to be a suboptimal dose, as the blankets would break in higher conditions. Hurst concluded that by increasing the ratio of influent turbidity to the dose, one could use a lower dose while still having the same rate of particle removal. The 2019 Spring HRS Plate Settlers team has considered the velocity and dose together. Hurst recommends a range of 1.0 to 7.5 mg/L of alum, so the team used those values in a predictive model of the plate settlers. In short, this provided the team control variables to use as a model for testing the plates. [Kanha said this research is not applicable to us, but I am a tad confused considering it gave us control variables to test with]

~~In contrast to studying dose, Garland (2017) observed how the characteristics of flocs that enter a sedimentation tank influence the performance of the tank. In Garland’s experiment, G, the velocity gradient of the water in the tank, was increased in a range of 74–251  $s^-1$ while residence time in the water, θ, was decreased. This is because they influence each other. They concluded that a constant Gθ of ~20,000 improved the particle removal. Because of this, a residence time of 24 s with a G of 251  $s^-1$ resulted in 14 NTU; however, after varying G to 72 $s^-1$, the minimum turbidity was found to be 0.15 NTU. Garland concluded that velocity gradients greater than the existing specifications could be applied to reduce the flocculation time. As a result, the effects of the velocity gradients upon the plates was heavily considered in the team’s designs.~~[-Addressed LM (Kanha said to remove this, as it is not applicable to our research. I agree.)]

The Summer 2018 Team discovered that at higher upflow velocities, the floc blanket was much more dense at the top of the recirculator than at the bottom. They proposed that the Fall 2018 team design a recycle line to allow for flocs at the top of the recirculator to flow back to the bottom and re-establish a more uniform distribution. The Fall 2018 Team responded to this observation via incorporation of a recycle line along the recirculator to improve floc blanket longevity. The installation of a recycle line resulted in decreased reactor performance, as the effluent turbidity resulted in a consistent ~30 NTU increase versus the baseline trial throughout the test. Furthermore, water tended to flow up both the recirculator and recycle line rather than down the recycle line.

Following this research, the Fall 2018 team decided that future work might involve incorporating a peristaltic pump along the recycle line to ensure proper direction of water flow, which would help them prove their initial hypotheses. Currently, Flow Recycle has been placed on standby as HRS: Plate Settlers develops plates to incorporate into the sedimentation tank. This is a similar goal as Flow Recycle’s; thus, HRS: Plate Settlers is an extension of Flow Recycle. All things considered, it was imperative that the subteam considered the density of the blanket as a function of the plate geometry, for that contributes to both flow recycle and plate settler research.

## Methods
HRS: Plate Settlers approached the plan of incorporating plate settlers by developing a CAD (Computer-aided design) model of the plate settlers apparatus. The tentative design (Figure 3, Figure 4) included modifiable slots to test variable angles of plate entry, and a tapered edge to ensure plate settlers are locked in place during experiments. This way, plate settlers cannot fall into the sedimentation tank and will not vary in angle or orientation during testing. The model is hollow besides the plate settlers themselves, thus allowing water and flocs to flow freely through the apparatus as flocs hopefully settle on the plates.

The plates used in the CAD model were PVC plates around 10 cm in length and 1 cm spacing, with thicknesses varying between 0.5 and 1 cm. In the actual printed design of the apparatus, 2mm thick PVC plates fit somewhat better than 3mm PVC plates, although it was found that the lack of a tapered edge in the PVC plate negatively affects its ability to fit into the 45 degree slot, thus preventing formation of a watertight seal. A watertight seal is crucial to the functionality of the apparatus to ensure that flocs settle on the plate surface and do not get lodged within the apparatus itself.

**[How do you plan on getting this watertight seal?]**[-Addressed LS/CO (addressed in results and future work)]

![2DDesign](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Setup/20190412_230917.jpg)

Figure 4. rinted design placed inside the testing-tank

Some further fabrication adjustments are required. 3D printing elicits some new issues, given that the material can produce a surface that could allow flocs to settle and prevent water from flowing through the apparatus. As an alternative design that HRS: Plate Settlers also worked on is a model wherein threaded rods are bound to the floc weir and inlet tube. Therefore, the plates were to be bound to either threaded rod. This allowed for less surface area for floc to settle on besides the plates.

Models for the plate settlers will be redesigned to test influences of plate width, spacing, and angle down the road, as is addressed in “Future Work” below. These variables are important given that plate width and spacing will likely influence the amount of space there will be for flocs and water to move freely through the sedimentation tank at the location of the plate settlers without creating a clumping of flocs, as was seen by HRS: Flow Recycle during testing when drilling and tapping the sedimentation tank (flocs settled on a small portion of the tap that was not flush with the sedimentation tank and slightly protruded inward). Angle may affect the actual settling of flocs, either preventing flocs from settling or not allowing flocs to fall back into the fall blanket and create a fluidized, free moving bed.

![PlateSettlers](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Labeled_Mock%20(1).png)

Figure 5.Design schematic of plate settlers apparatus showing latching mechanism and spacing between plates.

![PlateSettlersModel](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Labeled_Mock_2.png)

Figure 6. Design schematic of plate settlers indicating modifiable slots and the tapered edges that prevent plates from slipping into the sedimentation tank.

**[2 dead links. You need the link to the raw file by opening the image in a new tab.]**

**[As of April 24 the links are still dead. Please address them!]**[-Addressed LM]

**[Please include in this document the operation and design of the tank of the HRS by updating the Methods and adding a Manual section]**[-Addressed LM]

After 3D printing the aforementioned settlers, problems arose regarding the use 3D printing itself. Residue was left on the plates after the plate-settler testing apparatus after it was made, and this prohibited a unified upflow throughout the tank. This residual material cannot be avoided, as it is part of the printing process. As a result, the team had to look to more methods of developing plate settlers, because the microscale technology necessary to 3D print the plates is not readily available in the AguaClara lab.

As a result, the team moved on to fabricating the device themselves. This consisted of the following procedure:
1) Drill holes in PVC plates that are smaller than a 1/8 in wire. This tolerance develops a friction fit that will be utilized in step 3
2) Cut a piece of 1/8 metal wire 400 mm in length. *Note: this length is subject to change based on design specifications.*
3) String the metal wire through the drilled holes.
4) Cut smaller wires that can be knotted along the main metal strip. These knots will fasten the plate settlers at the angle desired.
5) Attach the wire to base-supports, as seen on both sides of Figure 7 and in the left of Figure 8.

![Settlers_v2_in_Design](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/Settlers_v2_in_Design.JPG)

Figure 7. The second version of settlers as seen from the lab setting.

![Settlers_v2_in_Design_2](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/Settlers_v2_in_Design_2.JPG

Figure 8. An upclose picture at the plate settlers as the fastening system.

This design achieves the same purpose as before, but does so without disrupting the uplfow of the sedimentation tank. This is achieved through the small profile of the metal wire.

## Results
Following fabrication of the plate settlers apparatuses, a major goal of the team was to incorporate all the necessary equipment that was previously lacking or outdated. In particular, the influent and effluent turbidimeters were replaced, ProCoDa method files were updated, and tubing was replaced over the course of the semester to account for several years of unkempt equipment. This replaced tubing consisted of: 
1) Flocculator tubing
2) Effluent and Influent Tubing
3) Tube settler tubing
4) Clay pump tubing
5) PACl tubing

Upon running the first trial, an initial issue faced was an error on the influent turbidimeter. Upon referring to the User’s Manual and performing a calibration test, the influent turbidimeter was functional. The latest development has been a successful test of simply filling the sedimentation tank with water and ensuring that water travels up the tube settlers out of the tank. The team considered this a baseline test and proof of concept. From this experiment, the following errors were found:
1) Leakage across the tank from the floc weir to the floc-bed side.
2) Leakage around the plate settlers, as the fit is not water-tight.

Lastly, while no tests to compare the second version of plate settlers were performed due to time constraints, these settlers are problematic. This is because of their flexible design, which allows for plate settler deformation over time, even when not in the sedimentation tank.

## Analysis
Considering the device was properly restroed this semester, a manual was written to explain the operation of this device. Through the baseline testing specified in results, it is clear of what needs to be addressed in order to fix these problems. While fixes for these issues is addressed is Future Work, the consequences of the results found is specified here.

Because there is leakage from the floc weir-to the bed, the upflow velocity was not in line with a theoretical calculation. This led to issues regarding miscalibrated data, etc. Furthermore, the leakage across leads to flocs flowing across the tank rather than up the tank. Considering the goal of this sedimentation tank was to create a floc bed, it proves problematic when its inherent design does not encourage that.

Furthermore, the team notes leakage around the plate settlers. This implies the desing is not water-tight, which was problemtatic in two regards. The first is that flocs can ecscape the bed that is developed, and that allows for flocs that typically would not pass the bed to enter the tube settlers. This was not reflective of the design of the sedimentation tanks in AguaClara plants, so fixing it is a priority. In a similar vein as the previous error, this led to a miscalibrated design, and effluent values were affected.

## Conclusions
No conclusions can be made on the current version of plate settlers, for no tests were carried out on the new design. The main focus of the team this semester to ensure the sedimentation tank carried out proper operation. While this goal was difficult to achieve considering no extensive prior documentation existed on the design, reverse-engineering the system proved valuable in this process.

By the end of the term, the team had a functional sedimentation tank with no external leaks, a functional ProCoDA setup, and all the necessary connections. Furthermore, the sedimentation tank has been cleaned both externally and internally, as well as emptied and ready for testing to begin on it.

The second version of plate settlers were not modified, and this allows other teams to observe the past work. Furthermore, future teams can use the model as a mock-up to develop their own standards and ideas for testing. Now that the sedimentaion tank is functional, data and results can be achieved easily and readily. Furthermore, as addressed in the manual, all operations of the tank have been documented.

Laslty, this team provided useful information in terms of what materials work for plate settlers and which do not. This is considering it is now known that ABS plastic does not work well for plate settlers, due to the residue. This implies future teams should continue testing with hand-fabricated designs.

## Future Work
HRS: Plate Settlers' next steps include performing baseline tests with the plate settlers apparatus. Following observation of these results, HRS: PS will perform subsequent experiments to determine how the effluent turbidity varies with changes in angle of the plates orientation, as well as with the alteration of variables such as number of plates, spacing of plates, and thicknesses of plates. 
As a majority of HRS: Plate Settler's efforts has gone into refurbishing the graduate-laboratory's sedimentation tank, by the end of the semester the team has been able to set it up, so it is ready for the next team to use. Considering no recent reports or information existed on this beneficial model, HRS documented the ways in which cleaning, pump operation, coding structure, and assembly of the mock-up. Additionally, well-a detailed manual regarding how to operate and run tests in the sedimentation tank was created. This ensured future teams have a better understanding of the designs, allowing more testing to take place.
**[Please include in this document the operation and design of the tank of the HRS by updating the Methods and adding a Manual section]**
When the testing of HRS: Plate Settlers was completed, there was still a large amount of unknowns regarding their operation, and that falls into the hands of future research. Despite the team's lack of time to carry out experimental-ideas this semester, there are some adjustments and potential variables that the team thinks will make the plate settler apparatus more functional, as well as some problems that need fixing in order to start testing again. The team did not have time to fix every issue with the tank, however, these minor errors can be corrected:
As a priority, that new team would have to open up the sedimentation tank itself and replace the inner pieces connecting the wier to the tank, due to the fact that some leakage has been noticed across the main section of the tank to the floc weir. 
Adding a second effluent pump to the tube settler with the intention of pumping water out of the tank at a higher upflow velocity. 
Connecting the plates in the apparatus with two wires across instead of one to make it easier to set the angle at which one wants the plates to be. 
Placing silicone on the sides of the plates to make them easier to slide in and out, and also providing a much tighter water seal. 
Making sure that the latching device on the right side of the tank is not deforming, which would cause the wire, and therefore, the plates to deform. This could be achieved by building it with metal and screws instead of PVC and glue. 
Finally, after all the problems are fixed, the new team should start experimenting with different kinds of materials, plate thickness, separation between plates, different kinds of wires, angles, etc. In this category, primarily the following concepts still need to be tested:
1) How does the type of material affect the operation of the settler?
2) How thin should a channel be before it gets clogged with flocs
3) How can plates be easily cleaned in their new design [speaking in future tense--no finalized design exists yet, hopefully by the final report there will be some however. If not, this will be removed]**[sounds good]**

## Manual [-Addressed LM]

Plate settlers are proven as beneficial devices that stabilize a floc bed, but their testing in the lab setting is unpredictable. Because floc beds currently break with ease, ensuring that plate settlers are optimized in their ability to stabilize a floc bed is crucial to AguaClara research. As a result, the motivation of HRS: Plate Settler's goal is not to prove whether or not implementing plate settlers benefits AguaClara Filtration. Rather, it is to test variables that can improve the longevity of the floc blanket in the lab-setting. Hence, the following variables exist in our hypothesis: [this feels a tad repetitious if its previously mentioned in the report, thoughts?]
1) Based on previous theory, it is known that the longest distance a floc can travel across a plate is determined by the equation referenced in Figure 3. Henceforth, when angle \alpha [why cant i get latex to work for greek letters?] is 45&deg;, the floc will spend the most time in the plate settler, and therefore: the floc bed will be created over the longest period of time. With such a long period, the bed will become more stable than before.
2) Furthermore, based on research performed by Hurst (2016), it is understood that a higher number of plates results in more stability. This signifies that the smaller the plates can get—and the more of them that can be inserted into the tank—yields the best results for floc blanket longevity.

While most materials already existed in the lab, little documentation existed regarding the creation of the sedimentation tank. Henceforth, this manual covers the creation of HRS Spring 2019's modifications and additions to the design:
**1x Clay Mixer**

**1x Clay Pump**

**2x Turbidity Meters (Influent/Effluent)**

**1x Influent Pump**

**1x PACl Pump**

**1x Effluent Tube Settler Pump (2 is recommended to operate at higher upflow velocities, but only 1 [Question for Kanha: is using 1 instead of one appropriate?] is currently in use)**

**6x 1 in Diameter, 5 ft Long Tube (for Tube Settlers)**

**1x 30 ft Role of 3 cm Poly-vinyl Tubing**

**1x HD-Pro Camera**

While the clay mixer runs at a constant rate when plugged in, the four pumps can have their rates adjusted. The following calculations of pump rates have been performed for 1mm/s of upflow, however, the methodologies are consistent with any upflow.

1) Use a timer and graduated cylinder to test the output of a pump at a certain RPM: ___ rpm = ___ mL/___ sec. Use that relationship in a proportionality consisting of the desired upflow. This will yield the desired RPM for that particular device. If working with multiple tube settlers, ensure that the team divides the desired upflow across the number of tube settlers
**Note: The cross sectional area of the tank's region of upflow (not including the floc weir) is 14 mm x 340 mm.**
2) If a pump measures in mL/minute instead of RPM, convert the RPMs to mL/minute using a dimensional analysis.
3) Using the above values, concentrations for stock of PACl and its respectful mL/min dosing can be calculated using the code [here](https://github.com/AguaClara/HRS-Flow-Recycle/blob/master/Preliminary_Calculations.md).

![Full_Setup](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/Full_Setup.png)

Figure 9. The Operational Setup of the Tank

![Setup_Labeled](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/Label_Setup_Labeled.png)

Figure 10. Labeled Components of the Setup

As for operation of the tank, consider Figure 5 above, which is the full set-up of interest. Within Figure 6, note the placement of each of the pumps and turbidity meters. PACl, Effluent (Tube Settlers), and Influent pumps all require the RPM or mL/minute to be manually set using the calculations found previously. Clay is automatically determined by ProCoDA based on influent readings, as it is the only pump connected to ProCoDA. The computer running ProCoDA is to the left of the set up in Figure 6.

![Tube_Settler_Setup](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/Tube_Settler_Connection.png)

Figure 11. Setup of the Tube Settlers

Figure 7 shows the way in which all tube settlers are operated by only one device. As mentioned in Future Work, it is advised for future teams to reconsider this choice and use two pumps to operate the tube settlers. This allows for upflow velocities higher than 1 mm/s.

The pumps and water should be turned on in the below order, for this procedure avoids pressure-build up and damage to the devices. Additionally, the values that HRS Plate Settlers used for a 1 mm/s upflow have been included.
1) Switch the blue tab near the sink into a position parallel with the tubing; this allows water into the system
2) Turn on the Influent Pump, as labeled in Figure 6. Use 143 mL/minute.
3) Turn on the PACl pump to 29.9 mL/minute.
4) Turn on the mixer by plugging it into the wall.
5) Turn on the Clay Pump.
6) Turn on the Tube Settler Pump to 94 rpm.
The device will now operate with standard procedures and for 1 mm/s of upflow through the sedimentation tank.

To power down the device, ensure that one first moves the blue valve mentioned in step 1 to a perpendicular position against the tube. After that, shut down of all devices can occur in any order.

*If the device does not operate as intended, the following troubleshooting can solve common errors:
- Calibrate the turbidity meters
- Ensure the influent valve is turned off when not in operation. This prevents pressure build-up and leakage.
- Verify the clay-mixer is properly turned on and not in contact with the side of the clay tub.
- Clean the tank using the sponge located beside it.
- Reconnect the sensors and pumps to ProCoDA after shutting down all components of the system.

## Bibliography
Balwan, K. (2016). Study of the effect of length and inclination of tube settler on the effluent quality. Journal (International Journal of Innovative Research and Advanced Engineering).

Culp, G., Hansen, S., & Richardson, G. (1968). High-Rate Sedimentation in Water Treatment Works. Journal (American Water Works Association), 60(6), 681-698. http://www.jstor.org/stable/41265352

Galantino, C., Oritz, A., & Zarecor, M. (2017). High Rate Sedimentation Fall 2017 Report.

~~Garland, C., Weber-Shirk, M., & Lion, L. W. (2017). Revisiting Hydraulic Flocculator Design for Use in Water Treatment Systems with Fluidized Floc Beds. Environmental Engineering Science, 34(2), 122–129. https://doi.org/10.1089/ees.2016.0174~~[-Addressed LM (removed based on Kanha's request]


Hong, A., Si, H. (2018). High Rate Sedimentation Summer 2018 Report.

Hurst, M. W. (2010). Evaluation of parameters affecting steady-state floc blanket performance. http://hdl.handle.net/1813/14755

Hurst M., Weber-Shirk M., & Lion L. W. (2017). Influence of Alum Coagulant Dose and Influence Turbidity on Floc Blanket Growth Rate, Steady-State Suspended Solids Concentration, and Turbidity Removal. Journal of Environmental Engineering, 143(2), 04016081. https://doi.org/10.1061

Swetland, K., Weber-Shirk, M., Lion, L. (2014). Flocculation-sedimentation performance model for laminar flow hydraulic flocculation with polyaluminum chloride and aluminum sulfate coagulants. Journal (Journal of Environmental Engineering).

Zarecor, M., Sharma, S., Conneely, J. (2018). High Rate Sedimentation Spring 2018 Report.

Sen, L., Conneely, J. (2018). High Rate Sedimentation Fall 2018 Report.
