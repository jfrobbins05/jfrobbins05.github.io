---
title: "Multi-Material Pliers"
excerpt: "Print-in place technique used to combine PLA and TPU"
header:
  image: /assets/img/pliers_4.jpg
  teaser: /assets/img/Pliers_4.jpg
gallery:
  - image_path: assets/img/pliers_4.jpg
  - image_path: assets/img/pliers_4.jpg
   
---


# The Project
This project aims to design print-in-place parts for pliers capable of picking up small objects such as a resistor. In order to accomplish this, two different materials (TPU and PLA) were needed to create strong, rigid handles and jaws with a flexible center to maneuver the jaws inward and outward.



# Print-In-Place
Print-in-place parts serve as an alternative to multi-material printing for applications that require multiple types of material properties. Print-in-place utilizes a single extruder 3D printer and requires detailed prototyping to allow parts to fit together snuggly without any complicated post-processing or assembly steps.

This process is not only applicable for pliers, but for many more complex applications. In a study performed by Rosa et al. specifically TPU and PLA (identical materials to the manufactured pliers) were utilized in a print-in-place Flexi-Hand and an Adaptive-Grip robotic system. The hand simulates the full movement of a real human hand with multiple joints at each finger while the Adaptive-Grip system serves as a grabbing aid for the physically impaired, both requiring both rigid and flexible components. These applications are intended to demonstrate the larger conclusion of the research that the print-in-place process is particularly useful for connecting flexible and rigid parts into one system. 

Also utilizing PLA and TPU, Hainswroth et al demonstrates the use of print-in-place parts for soft robotics with a flexible actuator. The study highlights print-in-place manufacturing as a strong option for morphological applications. In a general sense, print-in-place technology allows for greater mobility and possibilities between links and joints with only a single extruder. Beyond just movement, print-in-place tehcnology can also be used for the combination of materials with different aesthetic qualities, temperature tolerances, or other material properties.



# Iteration 1

![Plier Iteration 1](/assets/img/pliers_1.jpg)

My initial printed pliers were unsuccessful for several reasons, many of which were related to their unnecessarily large scale. The flexible TPU component in the center was very was_____, resulting in weakness and flexibility in the direction perpendicular to the movement of the pliers. The size also resulted in bulky handle and jaw components, applying a lot of weight on the flexible TPU portion and adding to their flimsiness.



# Iteration 2

![Pliers Iteration 2](/assets/img/Pliers_2.jpg)

In my next iteration, I scaled down the entire design and adjusted the infill material to have a width of 1.2 by over-extruding the nozzle and increasing the density to be proportional to the support need for pliers that size.


# Iteration 3

![Pliers Iteration 3](/assets/img/Pliers_3.jpg)

While the scale and functionality of the center TPU piece was successful in this iteration, the pliers were unusable since the offset of the trapezoidal joinery was too great and the PLA and TPU parts were not holding together. In my next iteration, I only reprinted the TPU center to enlarge the joinery so there was no longer an offset The pieces now fit together and the pliers were functional, but a few issues still presented themselves. The joinery was still not as strong as desired, the plier jaws only came together at one single point, and the part was still flexing mildly in the direction perpendicular to the shear of the pliers.

# Iteration 4 & Testing

![Pliers Iteration 4](/assets/img/pliers_4.jpg)

In my final iteration I resolved these issues by making minor adjustments to the CAD model and reprinting both parts of the pliers. I added a notch at the end of the jaws, creating a larger surface area for grabbing and an angle at which they meet flushly. I adjusted the offset to allow the two parts to slightly overlap by ____ in CAD, giving them a snug fit due to the flexibility of the TPU and the slight rounding of corners when printed. Finally, I extruded the entirety of the part 3 mm higher to give it greater thickness and enhanced stability in the perpendicular direction.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811bf98db0a920a9ac0?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Final Print Settings and Specifications
These settings and specifications were utilized in the final iteration of pliers:


PLA (Handles and Jaws)
- Infill Density: 15% (default)
- Infill Angle: 45 degrees (default)
- Infill Shape: Rectilinear (default)
- Extrusion Width: 0.6 mm (default)
- Horizontal Shells Solid Layers
    - Top: 3
    - Bottom: 3

TPU (Center Component)
-	Infill Density: 14%
- Infill Angle: 45 degrees (default)
- Infill Shape: Rectilinear
-	Extrusion Width: 1.2 mm (over-extruding with 0.6 mm nozzle)
-	Horizontal Shells Solid Layers
    - Top: 0
    - Bottom: 0

![Super Slicer](/assets/img/Super_Slicer_Center.png)

Key Plier Dimensions
- Full Length: 156.74 mm
- Jaw Length: 39.12 mm
- Jaw Capacity: 8.00 mm

# Citations
Hainsworth, T., Smith, L., Alexander, S., MacCurdy, R. (2020). A Fabrication Free, 3D 
    Printed, Multi-Material, Self-Sensing Soft Actuator. IEEE Robotics and Automation 
    Letters, vol. 5, no. 3, 4118-4125. doi: 10.1109/LRA.2020.2986760.

Rosa, F., Bordegoni, M., Dentelli, A., Sanzone, A., & Sotgiu, A. (2017). Print-in-place 
    of interconnected deformable and rigid parts of articulated systems. Procedia 
    Manufacturing, 11, 555–562. https://doi.org/10.1016/j.promfg.2017.07.149.

