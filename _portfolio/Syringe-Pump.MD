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

# Features

* **Fitted carriage compartments to snuggly hold 100 mL and 50 mL syringe sizes** With a build envelop just shy of 4 feet in all dimensions, the LF3DP is capable of printing furniture and other large objects.
* **High Volumetric Output Extruder: 1 kg/hr - 450 C.** This printer come standard with a MDPH2 extruder by Massive Dimension, which can extrude at a rate of 1 kg/hr. Unlike typical filament extruders, the MDPH2 uses a screw to convey and liquify plastic pellets before the molten material is pushed out of a large nozzle (1 to 5 mm extrusion diameter). Please note: This printer can also be configured for other high flow rate extruders, such as the Typhoon and Pulsar by Dyze Design.
* **Affordable Pellet Feedstock** Pellets are the cheapest form of feedstock for any plastic-based manufacturing process. Save 50-75% of material costs by using pellets instead of spools of filament. Concentrated colorant can be added to the virgin material to achieve any color in the rainbow without requiring large amounts of storage. Recyled material can also be used for sustainable material printing.

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

{% include gallery caption="Syring Pump Gallery" %}
