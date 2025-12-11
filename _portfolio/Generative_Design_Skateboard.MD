---
title: "Generative Design Skateboard Hanger"
excerpt: "Nylon-printed prototype for a lightweight skateboard hanger"
header:
  image: /assets/img/GD_Skateboard_ALSi10Mg_Rendering.png
  teaser: /assets/img/GD_Skateboard_ALSi10Mg_Rendering.png
gallery:
  - image_path: assets/img/GD_Skateboard_ALSi10Mg_Rendering.png
  - image_path: assets/img/GD_Skateboard_ALSi10Mg_Rendering.png
   
---
by Jacy Robbins

# Applications of Generative Design with Powder Bed Printing



# Generative Design Skateboard
With this ability for light weight and custom parts, generative design was utilized to combine two separate components of a motorized skateboard hanger into one. An existing hanger was used for dimensioning and identifying geometries; however, it was not utilized as a starting geometry to expand the possibilities for the part. Fusion 360’s preserve geometry, obstacle geometry, and load case features were utilized to maintain imperative connecting regions of the hanger, leave space for other necessary components as well as assembly, and simulate the actual forces and moments that would be applied to the hanger. Additionally, two different materials, Nylon and Aluminum, were generated to compare outcomes of different materials.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811790e8f4336c81568?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b60281106e8f2f7b21c50dd?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Preserve and Obstacle Geometries
![Preserve Geometries and Loads](/assets/img/Preserves_and_Loads.png)
Figure 1: Preserve geometries and load cases in the Fusion generative design workspace

Preserve geometries were used for a few key elements of the design to ensure that imperative geometries remained intact, but sparingly in order to maximize the software’s generative design possibilities. Cylindrical geometries with through holes were maintained on either side of the hanger to support the wheels and steel axle (as seen along with other geometries in Figure 1). Additionally, a slot for the motor as well as its four screws were maintained with clearance to allow for tightening of the belt. Finally, a circular geometry and domed geometry were maintained for the hanger to fit on both the king pin and base plate respectively.

![Fully Assembly](/assets/img/Preserves_and_Loads.png)
Figure 2: Fully assembled skateboard including generative design hanger

One error in the original preserve geometry was the hole for the king pin which did not have significant clearance to be assembled even though there was sufficient room for the king pin. This error was resolved in the second iteration as can be seen in Figure 2 where the hanger and other skateboard components are fully assembled.

![Full Assembly](/assets/img/Obstacle_Geometry.png)
Figure 3: Obstacle geometries in the Fusion generative design workspace

Obstacle geometries were used to indicate where other components of the skateboard would be and clearances for assembly. Geometries slightly exceeding the size of the wheels, king pin, bearings, washers, axle, pulleys, motor, and spaces for the screws were included to prevent the generative design from creating any material that would interfere with these parts. Additionally, some areas required extra clearance for assembly such as above the bearings to ensure that they could be put on the king pin. Finally, an offset ground was modeled as an obstacle geometry to prevent any material from being generated too close to the theoretical ground which would impede the ability of the skateboard to lean. All of these obstacle geomteries can be seen in Figure 4.

![Colliding pulley](/assets/img/Preserves_and_Loads.png)
Figure 4: Original hanger design colliding with the pulley system

An error that manifested in the obstacle geometry was not accounting for clearance for the belt connecting the pulleys. Since it’s a less substantial geometry and was not included in the base Fusion model being designed off of, this clearance was left out of the first iteration of the design, causing the pulley to be mildly impeded by the geometry of the hanger as seen in Figure 3. This was resolved in the next design as can be seen in the clearances on either side of the pulley shown in Figures 5 and 6.

![Clearance for Pulley](/assets/img/IMG_7497.jpg)
Figure 5: Second hanger design providing clearance between the hanger and the pulley system on bottom side

![CLearance for Pulley 2](/assets/img/IMG_7502.jpg)
Figure 6: Second hanger design providing clearance between the hanger and the pulley system on top side

## Applying Loads
Several load cases were applied to the preserved geometries of the hanger as seen in Figure 1. These forces and moments were estimated with the weight of the motor and of a human body, but more precise methods could be utilized as well. To improve this process, Fusion 360 could be used in conjunction with other software such as Staad Pro or SolidWorks which could more accurately distributed component-by-component loads off a few key data points. The loads determined necessary for this project are as follows:

* **Structural Constraint:** The structural constraint was placed at the domed end of the hanger touching the base plate. This placement was selected since the domed end is held in the pivot cup which connects to the rest of the skateboard making it an appropriate spot for an anchor. Structural constraints impact the load paths of the geometry and it seems intuitive for the load paths to connect back to the anchor of the skateboard since that’s where many of the loads are originating from. The resulting material will be significant near the constraint to support these load paths.

* **X Moment on Motor Mount:** The moment in the X direction on the motor mount is applied by the torque of the motor and was determined by the maximum torque listed in the motor product description.

* **Y Moment on Motor Mount:** The moment in the Y direction on the motor mount is applied by the weight of the motor itself and was determined by the weight of the motor listed in its product description as well as the distance between its center of mass and the mount.

* **Z Moment on Motor Mount:** The moment in the Z direction on the motor mount I applied by the tension of the belt being pulled by the pulley. This magnitude was determined utilizing the torque of the motor on the pulley system and the distance of the belt from the motor mount.

* **Torque on Hanger Ends:** The torque on the hanger ends is applied by a twisting motion as someone leans on the board. The magnitude of this torque was determined by human body weight and approved AI assistance.

* **Forces on Hanger Ends:** The forces on the hanger ends come directly from the vertical forces of the person on the board. This force was determined from human body weight and distributed between the two ends as well as the bearing load on the king pin.
Bearing Load on King Pin Hole: See above.

Note: The applied loads in the model were based on a maximum body weight of 300 pounds.


# Nylon vs Aluminum
Two material options were provided for this generative design and resulted in vastly different outcomes despite having the same preserve, obstacle, and load parameters. The aluminum, being the stronger of the two, resulted in a much slimmer design which utilized far less material as seen in Figure 7. The nylon alternative resulted in a much bulkier design (seen in Figure 8) and emphasized the importance of significant obstacle geometry since material generated outside of what would be intuitively expected.
The slimmer aluminum design was printed out of Nylon on a pSLS printer for prototyping purposes. Although this printed part would not be sufficient for actual use, it represents a more promising and material-efficient option which could be executed on Vanderbilt University’s mSLS printer now that assembly has been confirmed. However, the Nylon alternative could be currently printed and effective, but would be costly and take up significantly more space in the pSLS print bed, limiting other parts that could be printed alongside it.

![Aluminum Design](/assets/img/GD_Skateboard_ALSi10Mg_Rendering.png)
Figure 7: Rendering of printed design intended to be made with ALSi10Mg

![Nylon Design](/assets/img/GD_Skateboard_Rendering_Nylon.png)
Figure 8: Hypothetical nylon design that could be printed using pSLS

# GD Benefits vs Drawbacks
At a broader scope, generative design capabilities are impressive, but perhaps not always necessary in part design. The technology can be useful for applications in which lightweighting is imperative such as aerospace, automotive, or medial fields. Additionally, the technology may be valuable if the current assembly process is particularly burdensome or a more ergonomic look/feel is desired. Finally generative design can be useful for brainstorming and prototyping. The generated load paths can give inspiration, illustrate efficient design strategies, or narrow down the most practical material even if the exact generative design is not utilized.
However, for production of everyday products generative design is likely not worth the computation power and revision process. Although generative design effectively combined two parts in our skateboard hanger, the assembly was not very complex to begin and the weight of the hanger was not significant to your average rider. 
Overall, the drawbacks of generative design are likely not worth the product for most applications. Generative design is an iterative process and computationally expense, possibly complicating the design process even though it may be simplifying assembly. Additionally, the increased cost to produce unique geometry would likely not be worth the payoff for most companies as it would require advanced printing or machining technologies. Although limitations can be applied to generative design models to account for machining capabilities, these often severely restrict the possibilities of the design and therefore limit the benefits of using generative design. Depending on the production method, the model may also require significant cleanup such as filleting and re-meshing to create a design that is production-ready. Finally, many generative design softwares make assumptions about linear material behavior and isotropic materials which are often not the case in reality. 


# Citations


