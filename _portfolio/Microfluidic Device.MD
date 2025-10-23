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
This application of PFF was designed with specifications in mind for particle size, successful sorting, and prevention of unwanted mixing. These specifications are as follows:
  1.  Overall size: The size of the device, 50 mm by 75 mm, was chosen to align with the size of an extra wide microscope slide. This size represents the upper end of microfluidic devices while still requiring minimal liquid compared to other medical devices.
  2.	Asymmetric Design and Channels Heights: An asymmetric design was chosen to sort the particles based on the necessary channel heights for these particular particle diameters. Channel heights were determined using the calculations below:
-	Height calculations
  3.	Flow Balance and Resistance: Based on particle and channel size discussed above, an uneven quantity of liquid is intended to flow into each channel. To keep flow consistent, allowing liquid to move through the device and to the outlet at an equal speed to avoid backflow, additional resistance was applied to channels to reduce flow rate. Calculations utilized to adjust resistance are seen below:
-	Resistance calculations
  4.	Channel Separation: Channels remained at least 1 mm apart to support the structure of the microfluidic device and not allow to make contact with each other
  5.	Channel buffer to wall: Channels were placed at least 3 mm from the edge of the mold so that the device has enough surface area to bond to the glass slide around the perimeter. This prevents leakage.
  6.	Device Height: The height of the device (excluding inlets and outlets) is 2 mm to allow sufficient space for the larger particle to move through the channel. This height signfiicantly exceeds the diameter of the larger particle to account for sagging in the device as its dimensions are relatively large for that of a microfluidic device.
  7.	Height of Ports: The height of the ports is 7 mm and is designed to slightly exceed the height of the mold frame. This allows tubing to be attached at both the inlets and outlets.
  8.	Inlet/Outlet Diameter and Spacing: Each inlet and outlet has a diameter of 2.2 mm to allow the tubing to be inserted into the device. The inlets and oulets also well exceed the 11 mm minimum necessary to fit multiple tubes next to each other during testing.
  9.	Pinch Section: The width of the pinch section is ~8.5 mm and within the recommended range of 6-10 mm necessary for creating an appropriate pressure drop as the particles enter the broad region of the device.
 10.	Broad Section: The broad section is ~20 mm, exceeding the minimum of 15 mm necessary for the parallel flows of liquid to migrate upward and adhere to the side of the device so that they are flowing at their proper respective heights into each channel.
  11.	Filleting: Filleting was used along the channels to prevent the formation of bubbles which causes flow restriction.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028115319aead2672a0d7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Developing a Usable Device
![Device Mold Image](/assets/img/device_mold.jpg)
This image shows the resin-printed microfluidic device mold.

After being resin printed, molds undergo a multi-step process to be made into microfluidic devices that maintain their structure and are not cytotoxic. Instructions for said process are as follows:
  1.	Create a Resin Printed 3D Mold: Resin printing molds for microfluidic devices are significantly cheaper and more accessible than the lengthy and complex   lithography alternative.
  2.	Post-Process the Mold: The mold must be washed in isopropyl alcohol and post-cured with UV light and heat in order to fully polymerize the resin and ensure that that the part has enough stability to continue the subsequent processes.
  3.	Apply Parylene Coating: The mold must be coated in parylene-C utilizing vapor deposition techniques in order to provide a protective barrier during casting as leaching of monomers from resins can be cytotoxic to cells and cause material degradation.

![Plasma Treating Image](/assets/img/Plasma-Treating-Image-2.jpg)
This image shows the plasma treating process.

  4.	Cast the Device: Mix PDMS and pour it into the mold. Then plasma treat it allowing covalent bonds to form and the material to harden before removal.
  5.	Seal the Device: The molded device is then sealed with a flat glass slide or another layer of PDMS on top to fully enclose the channels and prevent the device from leaking.

![Final Device Image](/assets/img/microfluidic_device.jpg)
This image shows the casted final microfluidic device.

# Results and Reflection

![Plasma Treating Image](/assets/img/device_setup.jpg)

![Plasma Treating Image](/assets/img/device_setup_upclose.pg)

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
