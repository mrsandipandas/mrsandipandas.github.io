---
title: "Observability-aware online multi-lidar extrinsic calibration"
collection: publications
permalink: /publication/2022-12-21-online-calibration
excerpt: "Accurate and robust extrinsic calibration is necessary for deploying autonomous systems which need multiple sensors for perception. In this paper, we present a robust system for real-time extrinsic calibration of multiple lidars in vehicle base frame without the need for any fiducial markers or features. We base our approach on matching absolute GNSS and estimated lidar poses in real-time. Comparing rotation components allows us to improve the robustness of the solution than traditional least-square approach comparing translation components only. Additionally, instead of comparing all corresponding poses, we select poses comprising maximum mutual information based on our novel observability criteria. This allows us to identify a subset of the poses helpful for real-time calibration. We also provide stopping criteria for ensuring calibration completion. To validate our approach extensive tests were carried out on data collected using Scania test vehicles (7 sequences for a total of ~ 6.5 Km). The results presented in this paper show that our approach is able to accurately determine the extrinsic calibration for various combinations of sensor setups."
date: 2022-12-21
venue: 'Submitted in ICRA'
paperurl: https://mrsandipandas.github.io/files/online-calibration.pdf
videourl: https://www.youtube.com/watch?v=aMWvWozBdrM
citation: 'Das, S., Klinteberg, L.A., Fallon, M. and Chatterjee, S., 2022. Observability-aware online multi-lidar extrinsic calibration. <i>arXiv preprint</i> arXiv:2212.09579.'
---