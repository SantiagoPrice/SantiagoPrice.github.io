---
layout: page
title: Project 1, A Neck Exoskeleton for persons Dropped Head Syndrome
description: Development and evaluation of compliant brace to assist the neck mobility of user with DHS
img: assets\img\mechanismScheme.png
importance: 1
category: work
related_publications: true
---


This project involves the design, development and evaluation of a compliant neck exoskeleton for patients with Dropped head Syndrome(DHS). This affection weekens the neck extensor muscles resulting in cervical kyphosis which severely deteriorates gait, breathing and swallowing. Current orthosis does not succesfully address this issues which motivated me to explore alternative alternative solutions to address this problem.

Our first achievement, came on the design of the actuation unit to support the head. Inspires by beam exoskeletons and continum robots, we design a multidirectional leaf-spring mechanism with adjustable stiffness. The core of the system is group of carbon fiber bars whose bending stiffness is adjusted by preloading the springs at the bottom shown in the figure.

This work which includes the teoretical model and experimental validation of the actuator and preeliminary user evaluation was presented at the Robosoft Conference 6th IEEE-RAS International Conference on Soft Robotics (RoboSoft).
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets\img\mechanismScheme.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    First prototype schematics. During flexion, the bottom end of the bars move compressing the springs. Preloading the springs with the adjustable plate modify the bar`s mechanical coupling regulating the system flexibility. {% cite santi_robosoft %}. 
</div>
 
The next design iteration involved increasing the stiffness range of the actuator to provide significant head support. Simultaneousky, we redesign the transmition sistem to decouple the head from the device during neck rotations, a motion that does not require to be assistided for DHS and is highly prevalent in activities of daily life. 
The system was evaluated in persons with no preconditions proving its effective adjustable support on the sagittal plane that does not constraining rotations. This work was published in IEEE Robotics and Automation Letters journal and will be presented at the ICRA@40 conference. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets\img\device_schem_back_front.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Device schematics. The actuation unit assist the head motion onthe saggital plan. The vertical rail transmit force on the orizontal plane of head only prenting to compress the spine. The horizontal raill allows free neck rotation {% cite santi_ral %}. 
</div>

At the current stage, we are starting clinical evaluation with end users to evaluate its effect on mobility. Our hypothesis is that the neck brace can enheance the neck posture and increase the range of motion of the neck. Stay tuned for upcoming updates.  