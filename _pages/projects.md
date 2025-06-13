---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}

## Tactile-Driven Dexterous In-Hand Writing via Extrinsic Contact Sensing

- 06/2024 - 03/2025
<!-- - Publication: R-AL 2025 -->
- Submitted to R-AL 2025
- Robotics X, Tencent / Manipulation Perception and Intelligence Lab, Shanghai Jiaotong University
- Advisor: Dr. Bidan Huang / Dr. Daolin Ma
<p align="center">
<iframe width="640" height="340" src="../files/Inhandwriting.mp4" title="Inhandwriting" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

Dexterous in-hand manipulation involving interactions between grasped objects and external environments remains a significant challenge in robotics. This study addresses in-hand manipulation under extrinsic contact through a three-finger handwriting task. We propose a hybrid arm-hand coordination framework combining reinforcement learning with compliance control for enhanced flexibility and robustness. Using tactile sensors embedded in each finger, our model dynamically predicts in-hand object pose and external contact, eliminating fixed contact state assumptions. The framework is validated in simulation, demonstrating accurate contact sensing across diverse writing tasks, and successfully transferred to the real world via systematic calibration and domain randomization. Real-world experiments showcase adaptability to various writing tools and trajectories, advancing robotic manipulation in unstructured environments.
[[Website](https://canzhopro.github.io/In_hand_Writing/)]


## iFEM2.0: Dense 3-D Contact Force Field Reconstruction and Assessment for Vision-Based Tactile Sensors

- 09/2022 - 02/2024
- Publication: IEEE T-RO 2025 + IROS 2026
- Manipulation Perception and Intelligence Lab, Shanghai Jiaotong University
- Advisor: Dr. Daolin Ma

<p align="center">
<iframe width="640" height="240" src="../files/iFEM2_Force.mp4" title="iFEM2_Force" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>
<p align="center">
<iframe width="640" height="350" src="../files/iFEM2_Force2.mp4" title="iFEM2_Force2" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

Vision-based tactile sensors provide rich tactile information through high-resolution images, enabling the reconstruction of dense 3D contact force fields. However, accurately recovering these forces remains challenging. This article introduces the multilayer inverse finite-element method (iFEM2.0), a robust approach for reconstructing dense contact force distributions. By integrating multilayer mesh constraints and ridge regularization, iFEM2.0 enhances reconstruction robustness. A systematic analysis of framework parameters is conducted through simulation and in situ mechanical calibration. Additionally, we establish a benchmark for evaluating 3D contact force perception in terms of accuracy, fidelity, and noise resistance. Both simulation and experimental results validate the effectiveness of iFEM2.0, providing critical force information for dexterous robotic manipulation.

[[IEEE Xplore](https://ieeexplore.ieee.org/document/10758225)] [[Website](https://canzhopro.github.io/iFEM2_Force/)]


## In-situ Mechanical Calibration for Vision-based Tactile Sensors

- 03/2022 - 09/2022
- Publication: ICRA 2023
- Manipulation Perception and Intelligence Lab, Shanghai Jiaotong University
- Advisor: Dr. Daolin Ma

<p align="center">
<iframe width="640" height="360" src="../files/Insitu_Calibration.mp4" title="Insitu_Calibration" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

This paper presents an in-situ mechanical calibration method for vision-based tactile sensors, enabling routine calibration of changing mechanical parameters over time without disassembly. Accurate calibration of Young's modulus and Poisson's ratio is essential for reliable force perception, yet existing methods are often cumbersome and impractical. Our approach leverages the sensor’s deformation sensing, an external force/torque sensor, and an indentation-based deformation-force model to extract these parameters efficiently. The method is validated by comparing finite element analysis (FEA) simulations with real indentation tests, demonstrating improved contact force distribution accuracy. This approach lays the foundation for lifelong routine calibration, enhancing tactile sensor applications in real-world manipulation tasks.

[[IEEE Xplore](https://ieeexplore.ieee.org/document/10161153)] [[Website](https://canzhopro.github.io/Insitu_Calibration/)]


