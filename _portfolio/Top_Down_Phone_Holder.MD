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
The component including the phone case and circle portion of the mechanism was printed out of TPU to allow some flexibility for the bearing ball to maneuver between notches. In contrast, the base of the detent mechanism was printed out of  ABS to provide a rigid surface for the spring to expand and contract against and a material with less friction for the circle to slide against. ABS was chosen instead of PLA due to PLA’s brittleness which would have been more prone to fracture during assembly. 
Similarly, ABS was chosen for the component attaching the mechanism to the bike as rigidity was needed to keep the assembly stable on the handlebars. Although also printed out of ABS, this component was designed separately for two reasons. Firstly, the complex geometry of combining this component with the other ABS print would have required an excessive amount of support material. Secondly, these pieces were printed at two different orientations, preventing any fracturing of the attachment component as it is being screwed on to the bike.
M5 nuts and bolts were selected for their appropriate size proportional to the design and their strong material properties which provide sturdiness in holding the components together.

# Dimensioning and Iteration

![Image of Phone Upright](/assets/img/IMG_6726.jpg)
Figure 3

![Image of Phone sideways](/assets/img/IMG_6726.jpg)
Figure 4

# Assembly Instructions
![Parts Separated Image](/assets/img/IMG_6726.jpg)
Figure 5

![Rendering Image](/assets/img/IMG_6726.jpg)
Figure 6

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811d3b0fece225a99d3?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>



# Citations


