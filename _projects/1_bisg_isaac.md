---
layout: page
title: bisg_isaac
description: Isaac Sim + PX4 digital twin of a ZED drone fleet
img: assets/img/projects/bisg_isaac.png
importance: 1
category: research
github: https://github.com/akashshingha850/bisg_isaac
---

A digital twin of a real drone fleet: **Isaac Sim + Pegasus Simulator + PX4** on the simulation side, **Jetson Orin NX + Pixracer (PX4) + ZED Mini** on the hardware side, and **ROS 2 Jazzy + MAVROS** as the one interface both share. Everything runs in Docker, so a simulated drone and a real drone are driven by the _same_ containers and code.

- Single-drone twin runs end to end on Isaac Sim 6.0: PX4 SITL, MAVROS and the real ZED SDK on a ZED Mini twin.
- GPS-denied by default: ZED visual-inertial odometry, rangefinder and optical flow fused in EKF2.
- Hosts the [Kinetix](/projects/2_kinetix/) whole-room capture flights.

{% include figure.liquid loading="eager" path="assets/img/projects/bisg_isaac.png" class="img-fluid rounded z-depth-1" %}

<div class="caption">Long-flight drift test in the simulated warehouse (5 laps, 359 m): EKF2 stays within 1.76 m of ground truth while raw ZED odometry drifts.</div>

[Source on GitHub →](https://github.com/akashshingha850/bisg_isaac)
