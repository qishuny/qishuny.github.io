---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## Contents

[Modeling Wheel Locomotion in Granular Media using 3D Resistive Force Theory and Sand Deformation Simulator](#modeling-wheel-locomotion-in-granular-media-using-3d-resistive-force-theory-and-sand-deformation-simulator)

[Extended Kalman Filter on Legged Robot](#extended-kalman-filter-on-legged-robot)

[Robot Localization and Mapping](#robot-localization-and-mapping)

[Robot Path Planning](#robot-path-planning)

## Modeling Wheel Locomotion in Granular Media using 3D Resistive Force Theory and Sand Deformation Simulator

<img src="/images/3DWheelExampleForce.png" width="49%"> <img src="/images/FEMMODEL.gif" width="49%">

The 3D Resistive Force Theory (3D-RFT) divides the intruder into segments and the net force of the body can be approximated by the linear superposition of the local stress at each segment.

In this paper, we apply the 3D-RFT method to rover wheel models and perform experiments for two different wheels in diverse slip-ratio and slip-angle environment profiles. To better capture the sand dynamics, we introduce a simple sand dynamics simulator to model the soil surface and combine it with 3D-RFT. The detail code can be found [here](https://github.com/qishuny/3D-RFT-wheel)

<hr style="height:3px;border-width:0;color:gray;background-color:gray">
## Extended Kalman Filter on Legged Robot

I am currently focusing on implementing a legged robot state estimator on a quadruped robot. The detail code can be found [here](https://github.com/robomechanics/quad-software)
<img src="/images/traj.png" width="39%"> <img src="/images/traj.png" width="39%">
<img src="/images/robotwalking.png" width="49%">

<hr style="height:3px;border-width:0;color:gray;background-color:gray">

## Robot Localization and Mapping

[Class projects](https://github.com/qishuny/Robot-Localization-and-Mapping) of CMU RI 16833 which we implemented particle filters, EKF, Linear and Non-Linear least squares problem, and point-based fusion.

<img src="/images/HW3result.png" width="29%">
<img src="/images/HW4result.png" width="49%">
<hr style="height:3px;border-width:0;color:gray;background-color:gray">
## Robot Path Planning

[Class project](https://github.com/qishuny/Path-Planning) of CMU RI which we implemented RRT, RRT*, A*, etc. algorithms.
<img src="/images/HW1result.png" width="49%">
<img src="/images/HW2result.png" width="49%">
