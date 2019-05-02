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

Figure 1: Design schematic of the sedimentation tank in the AguaClara plants.

![SedTankDiagram](https://github.com/CarmenOrtega/aguaclara_tutorial/blob/master/SedTankDiagram.PNG?raw=true)

Figure 2: Design schematic of experimental apparatus. Influent enters the sedimentation tank from the flocculator via inlet jet tubes of variable size. Downward direction of the influent flow is redirected upward by the semicircular jet reverser bottom geometry. Small percentage of the flow is insufficient to supply an additional tube settler and was sent to waste (Garland (2017).

The HRS team aims to design a tank that will yield an effluent turbidity of no more than 0.3 NTU while maintaining high upflow velocity. Operating at a higher upflow velocity will allow for a greater volume of water processing in a given period of time, which will decrease plant operating costs. However, when operating at a high upflow velocity in lab, the floc blanket is unstable. The blanket is dense near the top of the recirculator, but very thin near the bottom. HRS: Plate Settlers plans to remediate this issue by incorporating a second set of plate settlers within the sedimentation tank itself. As more particles enter through the manifold, flocs at the top of the blanket overflow into the floc hopper or floc weir. The smallest particles which make it past the floc blanket and floc hopper then enter the plate settlers. Plate settlers catch the smallest particles by increasing the horizontal space where particles can settle out. Plate settler length, channel-width (how far apart each plate is from its neighbor), and angle from the horizon determines capture velocity.

In order to ensure floc blanket stability, the team proposes 45&deg; to be the ideal plate-angle. This is operating under the hypothesis that plate settlers follow the principles that govern particle capture in a tube settler. Henceforth, based on the Figre 3, angle $\alpha$ is 45&deg;.

![longest_path](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Archive/longest_path.png)

Figure 3: Longest possible path of a floc through a sedimentation tube

By increasing the number of plate settlers, and thereby the area in which the flocs can settle, HRS: Plate Settlers intends to increase the capture velocity and therefore achieve a more stabilized floc blanket. In order to test this, a proper model-tank and experimentation system must first be developed. If successful, this will allow future teams to continue researching the potential viability of high upflow velocities in AguaClara plants. Furthermore, progress in the context of plate settlers held significance in two ways: a major improvement for High Rate Sedimentation as a subteam and for the process of flocculation in the overall water treatment process. Such advances would achieve a long-term goal of improving floc blanket stability (and thus improve the entire particle removal process) at both a model and real-life scale.

## Literature Review and Previous Work
Several past researchers have studied the process of sedimentation and the properties of floc blankets. Their research gives valuable insight to the Spring 2019 High Rate Sedimentation AguaClara team.

Culp et al. (1968) researched different angles to find the optimal slope of tube settlers: tubing that forces loose-flocs back into the sedimentation tank. Using normal laboratory conditions, a 60 degree angle with respect to the horizontal provided continuous sludge removal while showing effective sedimentation performance. This gave the team an angle to begin their designs at.

Furthermore, Hurst (2010) noted that the presence of the floc blanket enhanced the removal of particles. Their experiments found that upflow velocities of 1.0 to 1.3 mm/s produced the best performance. Past HRS teams have been successful at establishing floc blankets at higher velocities than the range given by Hurst, up to 15 mm/s, but those floc blankets were not stable; therefore, in order to ensure stability the team will use the velocities aforementioned by Hurst. A longer definition of the floc blanket and its purpose can be found in the introduction. [once again, we can define this here if you believe we should, however it would be long and not connected to the research paper at hand.] **[As I said above intro should be above previous work/lit review. Again sorry about that.]**

In regards to controlling a blanket effectively, Swetland (2014) discovered that as larger flocs formed in the sedimentation tank, those flocs would settle due to their high density relative to the fluid. Additionally, they found that in order for particle removal to occur, flocs need to have a higher settling velocity than the capture velocity. [We added this to better connect to our research]**[Great!]** The capture velocity is the lowest velocity at which plates can catch particles, while the settling velocity is the optimal and averaged speed for flocs to descend at. As the flocs concentrate and fall to the bottom of the sedimentation tank, a floc blanket forms. [while kanha told us to perhaps define these terms in this section, it seems a little odd here]**[Again you can define it in intro now that it will be above prev work+lit review]** These findings informed the High Rate Sedimentation teams' understanding of floc formation, so that they could designed a plate geometry that accommodates this settling and formation.

In a similar vein, Balwan (2016) explored how the length of the tube settlers affected effluent turbidity. He found that increasing the length of tube settler increased the amount of particles removed by the reactor. With tube settlers at an angle of 45 degrees and 60 cm length, turbidity removal was measured to be 80 percent. However, his experiments only had three length variables (40cm, 50cm, 60cm) and the effluent of longer tube settlers were unknown. As a result, the initial design for the plate settlers had plastic at a 45 degree angle. The angle is crucial in determining the effectivity of the plate settler in increasing upflow while decreasing turbidity. This is due to the proportional interaction that channel geometry has with the velocity gradient, which is discussed in Casey Garland's 2017 research below. [It seems logical to place Garland's research immediately afterwards, but then this section would not be in chronological order]**[Understood.]**

Hurst (2016) derived that rather than just increasing the upflow velocity to increase the creation of the floc blankets, alum dosage must also be considered. The turbidity and upflow velocity work in tandem to determine the stability of a suspended floc blanket. In the experiments described in Hurst (2016), upflow velocity was held constant at 1.2 mm/s, but coagulant doses (ranging from 1.0 to 7.5 mg/L) were varied in 10 nephelometric turbidity units between 100 NTU and 500 NTU. That being said, 15 mg/L of alum was found to be a suboptimal dose, as the blankets would break in higher conditions. Hurst concluded that by increasing the ratio of influent turbidity to the dose, one could use a lower dose while still having the same rate of particle removal. The 2019 Spring HRS Plate Settlers team has considered the velocity and dose together. Hurst recommends a range of 1.0 to 7.5 mg/L of alum, so the team used those values in a predictive model of the plate settlers. In short, this provided the team control variables to use as a model for testing the plates.

In contrast to studying dose, Garland (2017) observed how the characteristics of flocs that enter a sedimentation tank influence the performance of the tank. In Garland’s experiment, G, the velocity gradient of the water in the tank, was increased in a range of 74–251  $s^-1$ while residence time in the water, θ, was decreased. This is because they influence each other. They concluded that a constant Gθ of ~20,000 improved the particle removal. Because of this, a residence time of 24 s with a G of 251  $s^-1$ resulted in 14 NTU; however, after varying G to 72 $s^-1$, the minimum turbidity was found to be 0.15 NTU. Garland concluded that velocity gradients greater than the existing specifications could be applied to reduce the flocculation time. As a result, the effects of the velocity gradients upon the plates was heavily considered in the team’s designs.

The Summer 2018 Team discovered that at higher upflow velocities, the floc blanket was much more dense at the top of the recirculator than at the bottom. They proposed that the Fall 2018 team design a recycle line to allow for flocs at the top of the recirculator to flow back to the bottom and re-establish a more uniform distribution. The Fall 2018 Team responded to this observation via incorporation of a recycle line along the recirculator to improve floc blanket longevity. The installation of a recycle line resulted in decreased reactor performance, as the effluent turbidity resulted in a consistent ~30 NTU increase versus the baseline trial throughout the test. Furthermore, water tended to flow up both the recirculator and recycle line rather than down the recycle line.

Following this research, the Fall 2018 team decided that future work might involve incorporating a peristaltic pump along the recycle line to ensure proper direction of water flow, which would help them prove their initial hypotheses. Currently, Flow Recycle has been placed on standby as HRS: Plate Settlers develops plates to incorporate into the sedimentation tank. This is a similar goal as Flow Recycle’s; thus, HRS: Plate Settlers is an extension of Flow Recycle. All things considered, it was imperative that the subteam considered the density of the blanket as a function of the plate geometry, for that contributes to both flow recycle and plate settler research.

## Methods
HRS: Plate Settlers approached the plan of incorporating plate settlers by developing a CAD (Computer-aided design) model of the plate settlers apparatus. The tentative design (Figure 3, Figure 4) included modifiable slots to test variable angles of plate entry, and a tapered edge to ensure plate settlers are locked in place during experiments. This way, plate settlers cannot fall into the sedimentation tank and will not vary in angle or orientation during testing. The model is hollow besides the plate settlers themselves, thus allowing water and flocs to flow freely through the apparatus as flocs hopefully settle on the plates.

The plates used in the CAD model were PVC plates around 10 cm in length and 1 cm spacing, with thicknesses varying between 0.5 and 1 cm. In the actual printed design of the apparatus, 2mm thick PVC plates fit somewhat better than 3mm PVC plates, although it was found that the lack of a tapered edge in the PVC plate negatively affects its ability to fit into the 45 degree slot, thus preventing formation of a watertight seal. A watertight seal is crucial to the functionality of the apparatus to ensure that flocs settle on the plate surface and do not get lodged within the apparatus itself.

**[How do you plan on getting this watertight seal?]**

![2DDesign](https://raw.githubusercontent.com/AguaClara/HRS-Flow-Recycle/master/Images/Setup/20190412_230917.jpg)

Figure 3. Printed design placed inside the testing-tank

Some further fabrication adjustments are required. 3D printing elicits some new issues, given that the material can produce a surface that could allow flocs to settle and prevent water from flowing through the apparatus. As an alternative design that HRS: Plate Settlers also worked on is a model wherein threaded rods are bound to the floc weir and inlet tube. Therefore, the plates were to be bound to either threaded rod. This allowed for less surface area for floc to settle on besides the plates.

Models for the plate settlers will be redesigned to test influences of plate width, spacing, and angle down the road, as is addressed in “Future Work” below. These variables are important given that plate width and spacing will likely influence the amount of space there will be for flocs and water to move freely through the sedimentation tank at the location of the plate settlers without creating a clumping of flocs, as was seen by HRS: Flow Recycle during testing when drilling and tapping the sedimentation tank (flocs settled on a small portion of the tap that was not flush with the sedimentation tank and slightly protruded inward). Angle may affect the actual settling of flocs, either preventing flocs from settling or not allowing flocs to fall back into the fall blanket and create a fluidized, free moving bed.

![PlateSettlers](https://github.com/AguaClara/HRS-Flow-Recycle/blob/master/Labeled_Mock%20(1).png)

Figure 4. Design schematic of plate settlers apparatus showing latching mechanism and spacing between plates.

![PlateSettlersModel](https://github.com/AguaClara/HRS-Flow-Recycle/blob/master/Labeled_Mock_2.png)

Figure 5. Design schematic of plate settlers indicating modifiable slots and the tapered edges that prevent plates from slipping into the sedimentation tank.

**[2 dead links. You need the link to the raw file by opening the image in a new tab.]**

**[As of April 24 the links are still dead. Please address them!]**

## Results
(We have not yet performed any tests, but we will be doing tests in the coming weeks for which we will show results in future report).

## Analysis
(We have not yet performed any tests, but we will be doing tests in the coming weeks for which we will show analysis in future report).

## Conclusions
(We have not yet performed any tests, but we will be doing tests in the coming weeks for which we will show conclusions in future report).

## Future Work
HRS: Plate Settlers' next steps include performing baseline tests with the plate settlers apparatus, which will be 3D-printed. PVC plates were inserted into the slots at a 45 degree angle initially. Following observation of these results, HRS: PS will perform subsequent experiments to determine how the effluent turbidity varies with changes in angle of the plates orientation, as well as with the alteration of variables such as number of plates, spacing of plates, and thicknesses of plates

As a majority of HRS: Plate Settler's efforts has gone into refurbishing the graduate-laboratory's sedimentation tank, a new task was created for HRS: document the operation and design of the tank. Considering no recent reports or information existed on this beneficial model, HRS documented the ways in which cleaning, pump operation, coding structure, and assembly are handled in regard to this mock-up. This ensured future teams have a better understanding of the designs, allowing more testing to take place.

**[Please include in this document the operation and design of the tank of the HRS by updating the Methods and adding a Manual section]**

When the testing of HRS: Plate Settlers was completed, there was still a large amount of unknowns regarding their operation, and that falls into the hands of future research. Primarily the following concepts still need to be tested:
1) How does the type of material affect the operation of the settler?
2) How thin should a channel be before it gets clogged with flocs
3) How can plates be easily cleaned in their new design [speaking in future tense--no finalized design exists yet, hopefully by the final report there will be some however. If not, this will be removed]**[sounds good]**


## Bibliography
Balwan, K. (2016). Study of the effect of length and inclination of tube settler on the effluent quality. Journal (International Journal of Innovative Research and Advanced Engineering).

Culp, G., Hansen, S., & Richardson, G. (1968). High-Rate Sedimentation in Water Treatment Works. Journal (American Water Works Association), 60(6), 681-698. http://www.jstor.org/stable/41265352

Galantino, C., Oritz, A., & Zarecor, M. (2017). High Rate Sedimentation Fall 2017 Report.

Garland, C., Weber-Shirk, M., & Lion, L. W. (2016). Revisiting Hydraulic Flocculator Design for Use in Water Treatment Systems with Fluidized Floc Beds. Environmental Engineering Science, 34(2), 122–129. https://doi.org/10.1089/ees.2016.0174


Hong, A., Si, H. (2018). High Rate Sedimentation Summer 2018 Report.

Hurst, M. W. (2010). Evaluation of parameters affecting steady-state floc blanket performance. http://hdl.handle.net/1813/14755

Hurst M., Weber-Shirk M., & Lion L. W. (2017). Influence of Alum Coagulant Dose and Influence Turbidity on Floc Blanket Growth Rate, Steady-State Suspended Solids Concentration, and Turbidity Removal. Journal of Environmental Engineering, 143(2), 04016081. https://doi.org/10.1061

Swetland, K., Weber-Shirk, M., Lion, L. (2014). Flocculation-sedimentation performance model for laminar flow hydraulic flocculation with polyaluminum chloride and aluminum sulfate coagulants. Journal (Journal of Environmental Engineering).

Zarecor, M., Sharma, S., Conneely, J. (2018). High Rate Sedimentation Spring 2018 Report.

Sen, L., Conneely, J. (2018). High Rate Sedimentation Fall 2018 Report.
