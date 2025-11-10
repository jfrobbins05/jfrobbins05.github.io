---
title: "Multi-Material Pliers"
excerpt: "Print-in place technique used to combine PLA and TPU"
header:
  image: /assets/img/IMG_6850.jpg
  teaser: /assets/img/IMG_6850.jpg
gallery:
  - image_path: assets/img/IMG_6850.jpg
  - image_path: assets/img/IMG_6850.jpg
   
---


# The Project
This project aims to design print-in-place parts for pliers capable of picking up small objects such as a resistor. In order to accomplish this, two different materials (TPU and PLA) were utilized to create strong, rigid handles and jaws with a flexible center part to allow for inward and outward manuevering. The pliers were designed to remain open when not in use.



# Print-In-Place
Print-in-place parts serve as an alternative to multi-material printing for applications that require a variety of material properties. Print-in-place utilizes a single extruder 3D printer instead of a multi-extruder printer, limiting complications during printing. However, this process requires detailed prototyping to allow parts to fit together snuggly without any complex post-processing or assembly steps.

Print-in-place technology is not only applicable for pliers, but for many more robust applications. In a study performed by Rosa et al, TPU and PLA (identical materials to the manufactured pliers) were utilized in a print-in-place Flexi-Hand and an Adaptive-Grip robotic system. The hand simulates the full movement of a real human hand with multiple joints at each finger while the Adaptive-Grip system serves as a grabbing aid for the physically impaired, both requiring rigid and flexible components. These applications are intended to demonstrate the larger conclusion of Rosa et al's research that the print-in-place process is particularly useful for connecting flexible and rigid parts into one system. 

Also utilizing PLA and TPU, Hainswroth et al demonstrates the use of print-in-place parts for soft robotics with a flexible actuator. The study highlights print-in-place manufacturing as a promising option for morphological applications which cannot be reduced to a single set of material properties. In a general sense, print-in-place technology allows for greater mobility and possibilities between links and joints with only a single extruder. Beyond just movement, print-in-place tehcnology can also be used for the combination of materials with different aesthetic qualities, temperature tolerances, or other material properties.



# Iteration 1

![Plier Iteration 1](/assets/img/IMG_6726.jpg)
Figure 1

My initial printed pliers (Figure 1) were unsuccessful for several reasons, many of which were related to their unnecessarily large scale. The flexible TPU component in the center had a side length of 70.80 mm, resulting in weakness and flexibility in the direction perpendicular to the movement of the pliers. It was also immeditaely apparent that the infill density was not sufficient for the side and that extrusion width needed to be increased as layers were not completely bonded together. The size also resulted in bulky handle and jaw components, applying a lot of weight to the center and adding to the flimsiness of the pliers.



# Iteration 2

![Pliers Iteration 2](/assets/img/Pliers_2.jpg)
Figure 2

In my next iteration, I scaled down the entire design, adjusting the center piece to have a side length of 35.36 mm which can be seen in the size comparison in Figure 2. I also adjusted the infill material to have a width of 1.2 by over-extruding the nozzle and increased the density to be proportional to the support need for pliers of this new size. While the scale and functionality of the center TPU piece was successful in this iteration, the pliers were unusable since the offset of the trapezoidal joinery was too great for this scale, causing the handles and jaws to slip out of the center piece.


# Iteration 3

![Pliers Iteration 3](/assets/img/Pliers_3.jpg)
Figure 3

In my next iteration (Figure 3), I only reprinted the TPU center to enlarge the joinery, eliminating the offset between the parts. The pieces now fit together and the pliers were functional, but a few issues still presented themselves and performance could certainly be improved. The joinery was still not as snug as desired, the plier jaws only came together at one single point, and the part was still flexing mildly in the direction perpendicular to the shear of the pliers.

# Iteration 4 & Testing

![Pliers Iteration 4](/assets/img/IMG_6850.jpg)
Figure 4

In my final iteration (Figure 4) I resolved these issues by making minor adjustments to the CAD model and reprinting all parts of the pliers. I added a notch at the end of the jaws, creating a larger surface area for grabbing and an angle at which they meet flushly. I adjusted the offset to allow the two parts to slightly overlap in CAD, giving them a snug fit due to the flexibility of the TPU and the slight rounding of corners when printed. Finally, I extruded the entirety of the part 3 mm higher to give it greater thickness and enhanced stability in the perpendicular direction. These adjustments proved very successful in improving the functionality and efficiency of the pliers. The final design can be viewed here:

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811bf98db0a920a9ac0?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Final Print Settings and Specifications
These settings and specifications were utilized in the final iteration of pliers:


PLA - Handles and Jaws
- Infill Density: 15% (default)
- Infill Angle: 45 degrees (default)
- Infill Shape: Rectilinear (default)
- Extrusion Width: 0.6 mm (default)
- Horizontal Shells Solid Layers
    - Top: 3 (deafult)
    - Bottom: 3 (default)

TPU - Center Component (Seen in Figure 5)
-	Infill Density: 14%
- Infill Angle: 45 degrees (default)
- Infill Shape: Rectilinear
-	Extrusion Width: 1.2 mm (over-extruding with 0.6 mm nozzle)
-	Horizontal Shells Solid Layers
    - Top: 0
    - Bottom: 0

![Super Slicer](/assets/img/Screenshot 2025-11-09 180640.png)
Figure 5

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

