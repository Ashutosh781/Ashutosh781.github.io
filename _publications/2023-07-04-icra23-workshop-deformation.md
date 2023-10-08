---
title: "3D Deformation Simulation for Vascular Tissue with 2D Medical Imaging"
collection: publications
permalink: /publication/2023-icra-workshop-deformation
excerpt: 'This work introduces a method to utilize 2D tomographic medical imaging for building and calibrating a simplified FEM simulation of 3D vessel structures.'
date: 2023-05-29
venue: 'Workshop on Representing and Manipulating Deformable Objects at IEEE ICRA 2023'
citation: 'A. Bal, A. Gupta, C. Morales, A. Dubrawski, J. Galeotti, H. Choset, ”3D Deformation Simulation for Vascular Tissue with 2D Medical Imaging,” IEEE International Conference on Robotics and Automation Workshop on Representing and Manipulating Deformable Objects (ICRA), London, UK, 2023'
---

Traditionally, simulators using the Finite Element Method (FEM) have been used to estimate deformations of 3D structures under applied forces. Porting this method to concealed anatomy such as vessels comes with its own set of challenges

1. The material properties of the tissue are not known exactly
2. Tissue is typically non-homogeneous material
3. The 3D shape of the entire vessel cannot be obtained easily
4. How do we ascertain that the simulation is realistic?

In this paper we present a method to utilize 2D tomographic medical imaging for building and calibrating a simplified FEM simulation of 3D vessel structures. This simulation mimics vessel compression due to forces from an ultrasound probe. We estimate the material properties in calibration by using an optimization for the Young’s modulus and Poisson’s ratio. This is achieved by maximizing the IoU area between the deformed vessels observed in real-world ultrasound images captured by a robot and vessel cross-section from the simulated deformed model. We propose that our method can be used to generate 3D training data for neural networks being developed to predict deformations.

[Link to the paper](https://deformable-workshop.github.io/icra2023/spotlight/27-Bal-Spotlight.pdf)
