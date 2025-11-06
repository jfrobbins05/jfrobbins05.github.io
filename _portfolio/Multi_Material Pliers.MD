---
title: "Multi-Material Pliers"
excerpt: "Print-in place technique used to combine PLA and TPU"
header:
  image: /assets/img/microfluidic_device.jpg
  teaser: /assets/img/microfluidic_device.jpg
gallery:
  - image_path: assets/img/microfluidic_device.jpg
  - image_path: assets/img/microfluidic_device.jpg
   
---


# The Project
This project aims to design print-in-place parts for pliers capable of picking up small objects such as a resistor. In order to accomplish this, two different materials (TPU and PLA) were needed to create strong, rigid handles and jaws with a flexible center to maneuver the jaws inward and outward.



# Print-In-Place
Print-in-place parts serve as an alternative to multi-material printing for applications that require multiple types of material properties. Print-in-place utilizes a single extruder 3D printer and requires detailed prototyping to allow parts to fit together snuggly without any complicated post-processing or assembly steps.

This process is not only applicable for pliers, but for many more complex applications. In a study performed by Rosa et al., specifically TPU and PLA (identical materials to the manufactured pliers) were utilized in a print-in-place Flexi-Hand and an Adaptive-Grip robotic system. The hand simulates the full movement of a real human hand with multiple joints at each finger while the Adaptive-Grip system serves as a grabbing aid for the physically impaired, both requiring both rigid and flexible components. These applications are intended to demonstrate the larger conclusion of the research that the print-in-place process is particular useful for connecting flexible and rigid parts into one system. In a general sense, print-in-place technology allows for greater mobility and possibilities between links and joints with only a single extruder. Although not as expansive, print-in-place can also be used for the combination of materials with different aesthetic qualities, temperature tolerances, or any other material property.



# Iteration 1

![Device Mold Drawing](/assets/img/IMG_6418.jpg)

My initial printed pliers were unsuccessful for several reasons, many of which were related to their unnecessarily large scale. The flexible TPU component in the center was very was_____, resulting in weakness and flexibility in the direction perpendicular to the movement of the pliers. The size also resulted in bulky handle and jaw components, applying a lot of weight on the flexible TPU portion and adding to their flimsiness.



# Iteration 2

![Device Mold Drawing](/assets/img/IMG_6418.jpg)

In my next iteration, I scaled down the entire design and adjusted the infill material to have a width of 1.2 by over-extruding the nozzle and increasing the density to be proportional to the support need for pliers that size.


# Iteration 3

![Device Mold Drawing](/assets/img/IMG_6418.jpg)

While the scale and functionality of the center TPU piece was successful in this iteration, the pliers were unusable since the offset of the trapezoidal joinery was too great and the PLA and TPU parts were not holding together. In my next iteration, I only reprinted the TPU center to enlarge the joinery so there was no longer an offset The pieces now fit together and the pliers were functional, but a few issues still presented themselves. The joinery was still not as strong as desired, the plier jaws only came together at one single point, and the part was still flexing mildly in the direction perpendicular to the shear of the pliers.

# Iteration 4 & Testing

![Device Mold Drawing](/assets/img/IMG_6418.jpg)

In my final iteration I resolved these issues by making minor adjustments to the CAD model and reprinting both parts of the pliers. I added a notch at the end of the jaws, creating a larger surface area for grabbing and an angle at which they meet flushly. I adjusted the offset to allow the two parts to slightly overlap by ____ in CAD, giving them a snug fit due to the flexibility of the TPU and the slight rounding of corners when printed. Finally, I extruded the entirety of the part 3 mm higher to give it greater thickness and enhanced stability in the perpendicular direction.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028115319aead2672a0d7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Final Print Settings and Specifications

-	Infill density: 14%
-	Width: 1.2 mm (using 0.6 nozzle over extruding)
-	No top and bottom layers – set to 0
-	TPU


# Citations
Rosa, F., Bordegoni, M., Dentelli, A., Sanzone, A., & Sotgiu, A. (2017). Print-in-place 
    of interconnected deformable and rigid parts of articulated systems. Procedia 
    Manufacturing, 11, 555–562. https://doi.org/10.1016/j.promfg.2017.07.149.
  bodies from cancer cell culture broth using tunable microfluidic systems. Sci Rep 7, 9907 (2017). 
  https://doi.org/10.1038/s41598-017-08826-w.

