---
title: "Microfluidic Device"
excerpt: "Medical device designed with thin channels to sort ______ for _________"
header:
  image: /assets/img/microfluidic_device.jpg
  teaser: /assets/img/microfluidic_device.jpg
gallery:
  - image_path: assets/img/microfluidic_device.jpg
  - image_path: assets/img/microfluidic_device.jpg
   
---


# Introduction to Microfluidic Devices and Applications 
Microfluidic devices are utilized to process small amounts of liquid (ex: 50 microliters) for medical applications. This processing can often take the form of mixing, sorting, or generating droplets with a microfluidic device and can be used for applications such as medical diagnostics, tissue engineering, pollution detection, or DNA sequencing. The device below is designed to sort particles based on size which can be applied to cells, viruses, sperm, blood components, fungal spores, metal particles, or extracellular vesicles.



# Introduction to PFF
This device utilizes Pinch Flow Fractination (PFF) to successfully sort particles.  PFF relies on laminar flow within the device in which streams of liquid flow parallel to each other with minimal, slow mixing, only from diffusion. This type of flow is possible as surface tension overwhelms typical forces on liquids such as gravity and inertia due to the high surface to volume ratio within microfluidic devices. This capillary action maintains the adhesive forces between the liquid and sides of the device, aiding in laminar flow.

PFF is superior to other filtering processes as it can be utilized for a wide variety of applications and further customized for certain specifications. One unique feature of PFF is its ability to sort droplets, a task that is particularly difficult with other common sorting techniques such as filtration or centrifugation. In a similar respect, PFF has a unique ability to sort extremely small particles or particles with minimal size differences, especially when AsPFF, a ______, is applied. In general, PFF benefits from the fact that the number of particles present in the fluid has no bearing on separation efficiency.

Once an application is determined, the geometry and details of a PFF microfluidic device can be altered for more customization than in other methodologies. For example, the flow rates at inlet branches can be adjusted for different particle size limits and necessary resistance prior to outlets can be adjusted with channel length. More specifically, the sedimentation effect can added with PFF to enhance the precision of sorting based on size or density and the shape of the pinch-to-broad transition can be adjusted to also enhance fractionation quality. Finally, tunable PFF utilizes a PDMS membrane valve connected to the out lets to independently control their flow rates and enhance separation accuracy.



# PFF Sorting as a Mechanism for ____
--



# Device Specifications and Dimensions

![Device Mold Drawing](/assets/img/IMG_6418.jpg)

This application of PFF was designed with specifications in mind for particle size, successful sorting, and prevention of unwanted mixing. These specifications are as follows:
  1.  Overall size: The size of the device, 50 mm by 75 mm, was chosen to align with the size of an extra wide microscope slide. This size represents the upper end of microfluidic devices while still requiring minimal liquid compared to other medical devices.
 2.	Pinch Section: The length of the pinch section is ~8.5 mm and within the recommended range of 6-10 mm necessary for creating an appropriate pressure drop as the particles enter the broad region of the device. The width of the pinched section was determined in relation with other factors to create realistic channel heights.
 3.	Broad Section: The broad section is ~20 mm long, exceeding the minimum of 15 mm necessary for the parallel flows of liquid to migrate upward and adhere to the side of the device so that they are flowing at their proper respective heights into each channel. The width of the broad section was determined in relation with other factors to create realistic channel heights.
  4.	Asymmetric Design and Channels Heights: An asymmetric design was chosen to sort the particles based on the necessary channel heights for these particular particle diameters. Channel heights were determined using the equations below with particle diameters in the ranges stated above:


## Unit Conversions

Convert particle diameters from micrometers to millimeters:

![](https://latex.codecogs.com/svg.image?140\ \mu m=\frac{140}{1000}=0.14\ mm)

![](https://latex.codecogs.com/svg.image?450\ \mu m=\frac{450}{1000}=0.45\ mm)

---

## Outlet Position Calculations

### Smaller Particle

![](https://latex.codecogs.com/svg.image?y_o=\left(w_p-\frac{D}{2}\right)\frac{w_b}{w_p})

![](https://latex.codecogs.com/svg.image?y_o=\left(1\ mm-\frac{0.14\ mm}{2}\right)\left(\frac{42\ mm}{1\ mm}\right)=39.06\ mm)

---

### Larger Particle

![](https://latex.codecogs.com/svg.image?y_o=\left(w_p-\frac{D}{2}\right)\frac{w_b}{w_p})

![](https://latex.codecogs.com/svg.image?y_o=\left(1\ mm-\frac{0.45\ mm}{2}\right)\left(\frac{42\ mm}{1\ mm}\right)=32.55\ mm)

Since these calculations provide the height of the particle center, additional space was factored in for particle radius. The significant difference between the necessary heights allowed for even larger channel entry points than these minimums, providing room for variation.

  5.	Flow Balance and Resistance: Based on particle and channel size discussed above, an uneven quantity of liquid is intended to flow into each channel. To keep flow consistent, allowing liquid to move through the device and to the outlet at an equal speed to avoid backflow, additional resistance was applied to channels to reduce flow rate. Calculations utilized to adjust resistance are seen below:

![](https://latex.codecogs.com/svg.image?R=\frac{12\mu L}{w,h^3})

![](https://latex.codecogs.com/svg.image?w_1=31\text{ mm},\quad L_1=15.351\text{ mm})

For 
𝑤 = 3.3

![](https://latex.codecogs.com/svg.image?L_2=15.351\times\frac{31}{3.3}=144.2\text{ mm})

For 
𝑤 = 7.6

![](https://latex.codecogs.com/svg.image?L_3=15.351\times\frac{31}{7.6}=62.7\text{ mm})


  6.	Channel Separation: Channels remained at least 1 mm apart to support the structure of the microfluidic device and not allow to make contact with each other
  7.	Channel buffer to wall: Channels were placed at least 3 mm from the edge of the mold so that the device has enough surface area to bond to the glass slide around the perimeter. This prevents leakage.
  8.	Device Height: The height of the device (excluding inlets and outlets) is 2 mm to allow sufficient space for the larger particle to move through the channel. This height signfiicantly exceeds the diameter of the larger particle to account for sagging in the device as its dimensions are relatively large for that of a microfluidic device.
  9.	Height of Ports: The height of the ports is 7 mm and is designed to slightly exceed the height of the mold frame. This allows tubing to be attached at both the inlets and outlets.
  10.	Inlet/Outlet Diameter and Spacing: Each inlet and outlet has a diameter of 2.2 mm to allow the tubing to be inserted into the device. The inlets and oulets also well exceed the 11 mm minimum necessary to fit multiple tubes next to each other during testing.
  11.	Filleting: Filleting was used along the channels to prevent the formation of bubbles which causes flow restriction.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028115319aead2672a0d7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



# Developing a Usable Device
![Device Mold Image](/assets/img/device_mold.jpg)
This image shows the resin-printed microfluidic device mold.

After being resin printed, molds undergo a multi-step process to be made into microfluidic devices that maintain their structure and are not cytotoxic. Instructions for said process are as follows:
  1.	Create a Resin Printed 3D Mold: Resin printing molds for microfluidic devices are significantly cheaper and more accessible than the lengthy and complex   lithography alternative.
  2.	Post-Process the Mold: The mold must be washed in isopropyl alcohol and post-cured with UV light and heat in order to fully polymerize the resin and ensure that that the part has enough stability to continue the subsequent processes.
  3.	Apply Parylene Coating: The mold must be coated in parylene-C utilizing vapor deposition techniques in order to provide a protective barrier during casting as leaching of monomers from resins can be cytotoxic to cells and cause material degradation.
  4.	Cast the Device: Mix PDMS and pour it into the mold. Then plasma treat it allowing covalent bonds to form and the material to harden before removal.
  5.	Seal the Device: The molded device is then sealed with a flat glass slide or another layer of PDMS on top to fully enclose the channels and prevent the device from leaking.

![Plasma Treating Image](/assets/img/Plasma-Treating-Image-2.jpg)
This image shows the plasma treating process.

![Final Device Image](/assets/img/microfluidic_device.jpg)
This image shows the casted final microfluidic device.



# Results and Looking to the Future of this Project
Testing did not result in successful sorting of small and large particles for several reasons. Tubes were connected to the inlets with a syringe on the opposite end while tubes connected to the outlets remained unconnected on the other end. As liquid was pumped into the device to prime it, significant bubbles formed, necessitating their removal through squeezing and tilting the device and pinching the outlet tubes. Once bubbles were removed, liquid containing the small and large particles was pumped into the device. While small particles successfully migrated to the top of the device and flowed down their respective channel, large particles appeared much more susceptible to resistance changes. Although the channels within the device were designed precisely to provide the correct resistance for flow rates through the 3 channels to be equal, small adjustments in the heights of the oulet tubes being held by hand caused significant resistance and drastic changes in flow rates. Due to this, the consistency of the large particle movement was weak and dependent on a steady hand.


![Device Set Up Image](/assets/img/device_setup.jpg)

![Device Set Up Up-Close Image](/assets/img/device_setup_upclose.jpg)



Based on these testing results, significant improvements can be made to account for resistance differences caused by external factors. A promising solution partially attempted by one student this semester was horizontal outlets for the device. However, this design can be improved upon. This semester, the horizontal outlets were incorporated on multiple sides of the device, eliminating flow differences due to tube height, but creating new variables such as the levelling the surface on which the device was placed. My proposed solution for these persistent flow rate issues is continuing the use of horizontal outlets, but limiting their use to one side of the device. By putting this constraint on the devices geometry, small errors in the level of the surface will affect outlets equally. Any small errors in the level of the surface in the direction perpendicular to the flow of the outlets would not affect this device design any more or less than that of a design with vertical outlets. Since this was not the primary issue with vertical outlets, and successful sorting has been performed with vertical outlets in the past when tubes were precisely positioned, the perpendicular angle of the device does not seem to bear a significant impact on flow rates.

Looking toward other future applications of these devices, it may be necessary that a device is capable of handling a wider range of particle sizes. Although there is potential to modify the device for this, there are also some limitations. If particle sizes varied minimally, it may be possible that channel heights could be maintained since they are designed with some room for variation. If the variation was more substantial, more channels could be added to account for more than 2 particle sizes. In this instance, not all channels would necessarily need to be used at once depending on the application. However, there is a limit to overall particle size that can be utilized in a microfluidic device due to its fluid dynamics. Microfluidic devices rely on surface adhesion of the liquid to the glass overcoming certain other factors such as gravity. If particle sizes necessitated channels too large, they make contian too much liquid for the principles of a microfluidic device to be maintained.



# Citations
Ashrafizadeh, S.N., Zare, M., Khatibi, M. A comprehensive review of pinch flow fractionation 
  in microfluidics: From principles to practical applications. Chem. Eng. Process. - Process 
  Intensif. 208, 110087 (2025). https://doi.org/10.1016/j.cep.2024.110087.

Florian, D. C., Intro to uFluidic Devices, Department of Engineering, Vanderbilt University, 2025.

O’Grady B. J., Geuy M. D., Kim H., Balotin K. M., Allchin E. R., Florian D. C., Bute N. N., 
  Scott T. E., Lowen G. B., Fricker C. M., Fitzgerald M. L., Guelcher S. A., Wikswo J. P., 
  Bellan L. M. & Lippmann E. S. Rapid prototyping of cell culture microdevices using parylene-
  coated 3D prints. Lab Chip 21, 4814–4822 (2021). https://doi.org/10.1039/D1LC00744K.

Sajeesh, P., Sen, A.K. Particle separation and sorting in microfluidic devices: a review. 
  Microfluid Nanofluid 17, 1–52 (2014). https://doi.org/10.1007/s10404-013-1291-9.
