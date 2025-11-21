---
title: "Bike Phone Mount"
excerpt: "Uses top-down modeling to create multiple components!"
header:
  image: /assets/img/IMG_6851 (2).jpg
  teaser: /assets/img/IMG_6851 (2).jpg
gallery:
  - image_path: assets/img/IMG_6851 (2).jpg
  - image_path: assets/img/IMG_6851 (2).jpg
   
---


# Top Down Modeling
Top-down modeling is a workflow utilized in CAD programs to simultaneously create multiple, separate components within one model. This process is extremely useful if dimensions of parts are based on other part sizes and pairs well with other Fusion 360 features such as parametric modeling and projections. If 3 key steps are followed, top-down modeling works seamlessly. They are as follows:
    1.	Always start by making a new component within the assembly.
    2.	Name the component immediately to prevent confusion.
    3.	Ensure that the component is activated before starting any sketches or making any changes pertaining to the component.


# Rotation Mechanism
The design was created using a simple, ball-and-spring detent mechanism. This mechanism (pictured in Figure 1 below) allows a bearing ball to slide between notches in a rotating circle. As the ball is pushed upward by the spring into the notch, the mechanism clicks into place allowing various positions at chosen intervals to be maintained. In this application, I utilized a detent mechanism to allow the user to click the phone's rotation into an upright position, a 90 degree position, and 3 intermediate positions in between for a total of 5 different orientations. This clicking mechanism can be viewed in motion in Figure 2.

To apply this mechanism to a phone case. A backing was added to the detent circle, allowing a screw to go entirely through the assembly and allow the circle to rotate freely without other movement. These pieces can be seen in Figure 5 which models the disassembled components.


![Image of Cross Section](/assets/img/IMG_6726.jpg)
Figure 1

![Rotation gif](/assets/img/pliers_gif.gif)
Figure 2

# Materials Selection and Printing Specifications
The detent circle and phone case component of the mechanism was printed out of TPU to allow some flexibility for the bearing ball to maneuver between notches. In contrast, the base of the detent mechanism was printed out of  ABS to provide a rigid surface for the spring to expand and contract against and a material with less friction for the circle to slide against. ABS was chosen instead of PLA due to PLA’s brittleness which would have been more prone to fracture during assembly. This variance in material and the potential need more multiple iterations made it most practical to filament print these parts as opposed to alternative methods such as resin or powder printing.

Similarly, ABS was chosen for the component attaching the mechanism to the bike as rigidity was needed to keep the assembly stable on the handlebars. Although also printed out of ABS, this component was designed separately for two reasons. Firstly, the complex geometry of combining this component with the other ABS print would have required an excessive amount of support material. Secondly, these pieces were printed at two different orientations, preventing any fracturing of the attachment component as it is being screwed on to the bike.
M5 nuts and bolts were selected for their appropriate size proportional to the design and their strong material properties which provide sturdiness in holding the components together.

# Dimensioning and Iteration

Dimensions were determined based on certain set parameters, but also adjusted throughout the 3D printing process, requiring one reprint of each part. The length, width, and depth of an iPhone 16 (the intended device for this product) were important in determining the dimensions of the phone case portion. Very minimal clearance was given in order to provide a snug fit with the friction of the TPU. The full length of the phone was not used since it would make the entire assembly much more top heavy which was not ideal for this application. Instead, around two-thirds of a phone length was used to ensure that it would be secure even at 90 degrees.

After printing, it was apparent that this was a flawed design as it left many of the phone’s important buttons compressed. Due to the snugness of this initial attempt, I felt comfortable reducing the overall size of the case and allowing it to hold only about half of the phone’s length. This modified design proved successful and allowed for a smaller rotating piece which became necessary in the next iteration of the other two components.

The original thicknesses of the base holding the spring of the detent mechanism as well as the component attaching the mechanism to the bike were designed to fit snuggly together. Additionally, the dimensions of the attachment portion were designed to fit snuggly on the handlebars. However, due to the conditions the assembly would be under on an uneven road, I felt that a more sturdy connection was needed for the vibrations of this application.
I redesigned both components to have 2 holes each to be connected with M5 bolts. Similarly, I added two holes for M5 bolts on the component connecting to the device so that it could be more securely attached. Although this makes the assembly process slightly more complex, it is still relatively simple and worth the tradeoff for a sturdy mount. Additionally, the lip of the attachment component came up higher on the base to allow for the bolt holes, necessitating the size of the rotating piece to be smaller for these two elements to not interfere as discussed above.


![Image of Phone Upright](/assets/img/IMG_6726.jpg)
Figure 3

![Image of Phone Sideways](/assets/img/IMG_6726.jpg)
Figure 4

# Assembly Instructions
![Parts Separated Image](/assets/img/IMG_6726.jpg)
Figure 5

![Rendering Image](/assets/img/IMG_6726.jpg)
Figure 6

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811d3b0fece225a99d3?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



# Citations


