---
layout: page
title: Robotic finger actuated by SMA
description: Tendon-driven mechanism based on shape memory alloys for controlling robotic fingers
img: assets/img/final_proto.jpg
importance: 2
category: work
related_publications: true
---

This work involved and development of a tendon driven mechanism for a robotic finger actuated by Nitinol wires. Nitinol is a Niquel-Titanium alloy with the particular property of recovering the shape when being heat up. In that sense, this elements can actuates as muscles when contracting by heat after being prestrech as the video shows. As observed, the diminute actuator is capable to move a much heavier, which makes this technology a promissing as a lightweight but powerfull actuation system for wearable devices. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Nitinol_lifting.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Nitinol spring lifting 400 grams of weight after applying heat. Source:  <a href="https://www.youtube.com/watch?v=-K57cbOhA5g&t=158s">Youtube</a>
</div>

The developed sistem consist on an anthropomorphic robotic finger driven by a Nitinol wire pair. This wires are heated by an electric current to move the fingers. The Protagonist wire function will bend the finger while the Antagonist wire will extend it. The following video illustrates the finger actuation cycle.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/actuacion_prototipo_final_1ciclo_enh.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Actuation cycle of the robotic finger. The protagonistic actuator bend the finger while the antogonistic one extends it. The actuators are heated by applying current. 
</div>

The finger mechanism is divided into two subsystems or units. The active unit involves the wire pair that directly act on the joint metacarpus. The passive unit involve a pair of Nylon tendons which couple the active motion of the metacarpal joint to the other two. Both units uses a winch in the metacarpal to control the wires and tendons pre-tension. On the finger side, the tendons wrap around the distal phalanx tip while the wires uses a custom-made self locking mechanism. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/final_proto.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/slice_and_side_view_prototype.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    1DoF antropomorphic finger. Parts are named according to the analogous bone of the human human.
    Plane of the underactuated design showing passive tendons and SMA wires arrangement along the finger. The wires directly actuates on the metacarpal joint while the remainning tendons couples this joint`s motion to the other 2. Consequently, the SMA moves to joints simultaneously.
</div>

Prior the final device, a simple prototype was made to evaluate the passive unit. This simple system consists on a finger-like kinematic chain mounted with the previously-mentioned nylon tendons. The system kynematics is tighly related to the cables normal distance to the joints, parameter that depends of the pulley's radius. The following video shows the mechanism motion when manually movimg the metacarpal joint.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/subactuated_module.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Prototype of the subactuated system that couples the movement of the three joints
</div>

The work scope is more extensive than what is here presented. I will soon update this post about development of the control unit to regulate the power supplied to the actuator.   