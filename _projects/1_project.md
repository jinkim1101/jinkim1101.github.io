---
layout: page
title: Inflatable Magnetic Soft Tactile Sensor
description: Soft tactile sensing for force, orientation, and contact-state estimation.
img: assets/img/inflatable-magnetic-soft-tactile-sensor.png
importance: 1
category: work
---

I developed an inflatable magnetic soft tactile sensor that converts physical contact into measurable force and contact information. The sensor combines a silicone dome, embedded magnet, and three 3-axis Hall sensors to estimate 3-axis force, contact orientation, and contact location while its compliance changes with internal air pressure.

## Contributions

- Designed the sensor hardware, including a 3D-printed base, silicone mold, and mold presser.
- Built a Hall-sensor pipeline that records nine magnetic-field signals and estimates the magnet's 5-DOF pose.
- Calibrated the model with physics-based synthetic data, then fine-tuned it using robot-collected measurements.
- Evaluated force and orientation estimates against ground-truth data collected with a UR robot and force/torque sensor.

## Results and next steps

Adding calibrated magnet-pose information reduced combined contact-orientation error by approximately 11% on held-out points. The next phase models free inflation separately from contact-induced deformation so the sensor can operate across changing air pressures and in a two-finger gripper.

[View the full project presentation]({{ '/assets/pdf/inflatable-magnetic-soft-tactile-sensor-presentation.pdf' | relative_url }})
