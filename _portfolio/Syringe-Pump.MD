---
title: "Syringe Pump"
excerpt: "Motor-powered syringe pump with adjustable speed settings and holsters for multiple syringe sizes"
header:
  image: /assets/img/FullSizeRender.jpg
  teaser: /assets/img/FullSizeRender.jpg
gallery:
  - image_path: assets/img/IMG_5202.jpg
  - image_path: assets/img/Syring Pump Rendering.png
   
---
Project Collaborators: Nathan Park, Isabella Blauzdys, Rylan Hunt

# Features

* **Fitted carriage compartments to snuggly hold 10 mL and 20 mL syringe sizes** Multiple syringe size options allow healthcare workers to select a syringe suitable for their particular application.
* **Adjustable extrusion speed** via Arduino code included below, the speed of extrusion can be easily customized to allow for liquids to be slowly released without manual syringe operation.
* **Heat/water-resistant configuration** Electrical technology is concealed within a compact box, protecting it from exposure to liquid in the syringe. The motor melting plate, which may heat up due to the motor, is designed with ABS plastic which has a high melting point.
* **Pausable motion system** Syringe pump can easily be paused to temporarily stop extrusion with the simple push of a button.
* **LED status indicator** LED light shines green for extruding, yellow for paused, and red for empty, allowing health care professionals to easily check the status of the syringe pump.

# Table of Components

| Component   | Preview                               | Quantity |
|-------------|---------------------------------------|----------|
| Base Plate  | <img src="assets/img/Screenshot 2025-08-31 193201.png" width="80"> | 1        |
| Bolt M6     | <img src="images/bolt.png" width="80"> | 4        |
| Nut M6      | <img src="images/nut.png" width="80">  | 4        |

# Arduino Code
<a href="assets/Arduino%20Code%20for%20Syring%20Pump%20Operation.pdf" target="_blank">
  Access Arduino Code for Pump Operation Here
</a>

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a44efc5598022b02e2?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Operating Instructions
Power the System 
* Connect the AC-DC power supply to a wall outlet. 
* Ensure that the 12V or 24V output (as configured) is securely connected to the motor driver circuit. 

Load the Syringe 
* Manually rotate the lead screw to retract the plunger carriage. 
* Insert either a 10 mL or 20 mL syringe into the designated holder. 
* Ensure the syringe barrel is seated firmly in the cradle with the barrel flanges pressed up against the end support, and the plunger flange slotted into the carriage 
* Secure the syringe and plunger using the mounting features. 

Select Syringe Size and Set Flow Rate 
* Before powering the system, the syringe size (10 mL or 20 mL) and the desired flow rate (in mL/min) must be set as constants in the Arduino code. 
* Once programmed and uploaded, the system will automatically calculate the correct motor speed based on these settings. 

Start the Pump 
* Press the latching button to start the pump. 
* The green LED will light up, indicating the pump is actively running. 

Pause the Pump 
* Press the latching button again to pause the pump if necessary 
* Both the green and red LEDs will turn on, creating a yellow color to indicate the pump is paused. 

End of Dispensing 
* When the syringe is nearing empty, the plunger will trigger the limit switch. 
* This will stop the motor automatically, and the red LED will turn on to indicate that the syringe is empty. 

Refilling or Replacing the Syringe 
* Disconnect the power supply. 
* Repeat the syringe loading process above. 
* Reconnect power, re-enter the syringe size and flow rate through the Serial Monitor, and restart the pump using the latching button. 

{% include gallery caption="Syringe Pump Gallery" %}
