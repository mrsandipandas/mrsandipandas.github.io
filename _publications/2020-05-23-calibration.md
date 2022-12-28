---
title: "Extrinsic Calibration and Verification of Multiple Non-overlapping Field of View Lidar Sensors"
collection: publications
permalink: /publication/2022-05-23-calibration
excerpt: "We demonstrate a multi-lidar calibration frame-work for large mobile platforms that jointly calibrate the extrinsic parameters of non-overlapping Field-of-View (FoV) lidar sensors, without the need for any external calibration aid. The method starts by estimating the pose of each lidar in its corresponding sensor frame in between subsequent timestamps. Since the pose estimates from the lidars are not necessarily synchronous, we first align the poses using a Dual Quaternion (DQ) based Screw Linear Interpolation. Afterward, a Hand-Eye based calibration problem is solved using the DQ-based formulation to recover the extrinsics. Furthermore, we verify the extrinsics by matching chosen lidar semantic features, obtained by projecting the lidar data into the camera perspective after time alignment using vehicle kinematics. Experimental results on the data collected from a Scania vehicle [~ 1 Km sequence] demonstrate the ability of our approach to obtain better calibration parameters than the provided vehicle CAD model calibration parameters. This setup can also be scaled to any combination of multiple lidars."
date: 2022-05-23
venue: 'ICRA'
paperurl: https://mrsandipandas.github.io/files/calibration.pdf
videourl: https://youtu.be/pSvWS1NxjM8
citation: 'Das, S., Mahabadi, N., Djikic, A., Nassir, C., Chatterjee, S. and Fallon, M., "Extrinsic Calibration and Verification of Multiple Non-overlapping Field of View Lidar Sensors," <i>IEEE International Conference on Robotics and Automation (ICRA)</i>, 2022, pp. 919-925.'
shortcitation: 'Das, S., Mahabadi, N., Djikic, A., Nassir, C., Chatterjee, S. and Fallon, M., <i>IEEE International Conference on Robotics and Automation (ICRA)</i>, 2022, pp. 919-925.'
---