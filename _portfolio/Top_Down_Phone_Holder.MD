---
title: "Bike Phone Mount"
excerpt: "Uses top-down modeling to create multiple components!"
header:
  image: /assets/img/Top_Down_Rendering.png
  teaser: /assets/img/Top_Down_Rendering.png
gallery:
  - image_path: assets/img/Top_Down_Rendering.png
  - image_path: assets/img/Top_Down_Rendering.png
   
---


# Top Down Modeling
![Rotation gif](/assets/img/Bike_Mount_GIF.gif)

Figure 1: Animation of phone rotating from upright to 90 degrees back to upright

Top-down modeling is a workflow utilized in CAD programs to simultaneously create multiple, separate components within one model. This process is extremely useful if dimensions of parts are based on other part sizes and pairs well with other Fusion 360 features such as parametric modeling and projections. If 3 key steps are followed, top-down modeling works seamlessly. They are as follows:
  1.  Always start by making a new component within the assembly.
  2.  Name the component immediately to prevent confusion.
  3.  Ensure that the component is activated before starting any sketches or making any changes pertaining to the component.


# Rotation Mechanism
The design was created using a simple, ball-and-spring detent mechanism. This mechanism (pictured in Figure 2 below) allows a bearing ball to slide between notches in a rotating circle. As the ball is pushed upward by the spring into the notch, the mechanism clicks into place allowing various positions at chosen intervals to be maintained. In this application, I utilized a detent mechanism to allow the user to click the phone's rotation into an upright position, a 90 degree position, and 3 intermediate positions in between for a total of 5 different orientations. This clicking mechanism can be viewed in motion in Figure 1.

To apply this mechanism to a phone case. A backing was added to the detent circle, allowing a screw to go entirely through the assembly and allow the circle to rotate freely without other movement. These pieces can be seen in Figure 5 which models the disassembled components.


![Image of Cross Section](/assets/img/Bike_Mount_Cross_Section.png)
Figure 2: Cross Section of detent mechanism in mount

# Materials Selection and Printing Specifications
The detent circle and phone case component of the mechanism was printed out of TPU to allow some flexibility for the bearing ball to maneuver between notches. In contrast, the base of the detent mechanism was printed out of  ABS to provide a rigid surface for the spring to expand and contract against and a material with less friction for the circle to slide against. ABS was chosen instead of PLA due to PLA’s brittleness which would have been more prone to fracture during assembly. This variance in material and the potential need more multiple iterations made it most practical to filament print these parts as opposed to alternative methods such as resin or powder printing.

Similarly, ABS was chosen for the component attaching the mechanism to the bike as rigidity was needed to keep the assembly stable on the handlebars. Although also printed out of ABS, this component was designed separately for two reasons. Firstly, the complex geometry of combining this component with the other ABS print would have required an excessive amount of support material. Secondly, these pieces were printed at two different orientations, preventing any fracturing of the attachment component as it is being screwed on to the bike.
M5 nuts and bolts were selected for their appropriate size proportional to the design and their strong material properties which provide sturdiness in holding the components together.

# Dimensioning and Iteration

Dimensions were determined based on certain set parameters, but also adjusted throughout the 3D printing process, requiring one reprint of each part. The length, width, and depth of an iPhone 16 (the intended device for this product) were important in determining the dimensions of the phone case portion. Very minimal clearance was given in order to provide a snug fit with the friction of the TPU. The full length of the phone was not used since it would make the entire assembly much more top heavy which was not ideal for this application. Instead, around two-thirds of a phone length was used to ensure that it would be secure even at 90 degrees.

After printing, it was apparent that this was a flawed design as it left many of the phone’s important buttons compressed. Due to the snugness of this initial attempt, I felt comfortable reducing the overall size of the case and allowing it to hold only about half of the phone’s length. This modified design proved successful and allowed for a smaller rotating piece which became necessary in the next iteration of the other two components.

![Image of Phone Upright](/assets/img/Bike_Mount_Upright.jpg)
Figure 3: Phone rotated upright in bike mount

![Image of Phone Sideways](/assets/img/Bike_Mount_90.jpg)
Figure 4: Phone rotated 90 degrees in bike mount

The original thicknesses of the base holding the spring of the detent mechanism as well as the component attaching the mechanism to the bike were designed to fit snuggly together. Additionally, the dimensions of the attachment portion were designed to fit snuggly on the handlebars. However, due to the conditions the assembly would be under on an uneven road, I felt that a more sturdy connection was needed for the vibrations of this application.
I redesigned both components to have 2 holes each to be connected with M5 bolts. Similarly, I added two holes for M5 bolts on the component connecting to the device so that it could be more securely attached. Although this makes the assembly process slightly more complex, it is still relatively simple and worth the tradeoff for a sturdy mount. Additionally, the lip of the attachment component came up higher on the base to allow for the bolt holes, necessitating the size of the rotating piece to be smaller for these two elements to not interfere as discussed above.


# Assembly Instructions

  1.  Insert the 1 x 8 x 12mm spring into the vertical hole in the detent mechanism base.
  2.  Balance the 8 mm ball bearing atop the spring
  3.  Place the detent circle phone holder atop the spring and keep the spring compressed. The phone holder should be facing upright, allowing a phone to be slid in from above.
  4.  While the spring remains compressed, insert the M5 x 22mm bolt through both the base and phone holder components and secure the back with an M5 nut.
  5.  Confirm the detent mechanism is working properly by listening for clicks into place as you gently rotate the phone holder clockwise.
  6.  Slide the detent base into the bike attachment's rectangular slot and secure with 2 M5 x 20mm bolts and nuts.
  7.  Slide the circular slot on the bike attachment on to an appropriate size bike handlebar.
  8.  Secure the attachment to the handlebar by inserting 2 M5 x 16mm bolts and turning nuts until the assembly is fixed in place.
  9.  Insert your phone!



![Parts Separated Image](/assets/img/Bike_Mount_Parts.png)

Figure 5: Bike mount parts disassembled

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811d3b0fece225a99d3?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
