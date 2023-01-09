---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

A. Machine learning surrogate models for fast computational analyses
------
Classical patient-specific simulations have limited clinical translatability, which can be attributed to one of the major bottlenecks of current technologies: they consist of multiple iterative computational steps and require a long computation time (hours to days), which is impractical for clinical decision-making. We developed a series of machine learning (ML) and deep learning (DL) approaches as fast and accurate surrogate models of cardiovascular simulations, for instance, (1) an image-to-image DL model as a fast and accurate surrogate of traditional finite element analysis to compute stress distributions; and (2) data-driven ML models for real-time inverse analysis of the aortic wall; (3) an ML-based surrogate model to directly assess failure metrics from aortic geometries. We built statistical shape models to generate large numbers of aorta geometries, yielding an effective strategy to gather mechanistic simulation data for training. By learning the high-dimensional input-output relationships, these ML and DL approaches can lead to fundamental improvements in computational performance, e.g., obtaining accurate results in real time.

<p align="center">
<img src="https://minliangliu.github.io//images/MLModel.png" width="337" height="256" />
</p>


B. Inverse identification of *in vivo* hyperleastic properties of the aortic wall from clinical images
------
We developed inverse methods to identify anisotropic hyperelastic material properties of the aortic wall from *in vivo* clinical multiphase images: (1) a novel multi-resolution direct search (MRDS) strategy based on updating finite element analysis; (2) a new inverse approach with a stress-matching based objective, in which the costly finite element simulations were avoided by using static determinacy of the aortic wall. For experimental validation, *in vivo* material properties identified from CT scans were compared to *ex vivo* responses obtained from biaxial testing of surgically resected tissue samples, and good matches between *in vivo* and *ex vivo* derived properties were obtained. The inverse methods can facilitate personalized computational assessment of cardiovascular diseases.

<p align="center">
<img src="https://minliangliu.github.io//images/InverseMethod.png" width="389" height="263" />
</p>


C. Neural network constitutive model and probabilistic failure metric
------
We performed mechanical tests of aortic tissue samples from 80+ patients. Using the experimental data, we developed novel constitutive model and failure criteria. (1) We established deep learning approaches as alternative solutions to model constitutive behaviors of soft tissues. Deep learning models that incorporate physical constraints and microstructural characteristics have led to performance improvements that could not be achieved by traditional constitutive models. For instance, we developed a generic, physics-informed neural network (PINN)-based model to learn tissue constitutive relation from biaxial testing data. We proposed a novel network architecture with a hierarchical learning strategy. Convexity constraints were imposed in the loss function to ensure that the model is physically relevant. The new model has only 3 constitutive parameters but demonstrated better fitting capability compared to classical models (e.g., 5-parameter Holzapfel model); (2) By using uniaxial testing data, we proposed a novel anisotropic failure criterion with dispersed fiber orientations; subsequently, we employed probabilistic modeling and derived a novel failure metric that incorporates variabilities of tissue strengths. The novel failure metric demonstrated a high discriminative power in the risk aortic assessment. 

<p align="center">
<img src="https://minliangliu.github.io//images/Constitutive.png" width="1284" height="406" />
</p>

D. Determination of growth evolution laws via reinforcement learning 
------
Growth evolution laws, which mathematically describe how living tissues change their shape in response to external stimuli, are required for modeling arterial growth. Traditionally, domain experts prescribe specific forms of growth laws by generalizing and inferring from limited experimental observations. We developed a reinforcement learning (RL) framework to automate the construction of growth evolution laws of arteries without the need for large experimental datasets. Our results demonstrated the capabilities of RL to effectively control the growth processes, and the predictions are in good agreement with experimental observations of adaptive arterial growth.

<p align="center">
<img src="https://minliangliu.github.io//images/Reinforcement.png" width="1336" height="222" />
</p>

E. Modeling of tissue fatigue damage and growth
------

We developed theoretical and computational models of tissue growth and fatigue damage: (1) an anisotropic volumetric growth model to incorporate the layer-specific and heterogeneous residual stress into patient-specific aorta geometries; (2) a damage mechanics model to predict fatigue properties of soft tissues based on the concept of residual stiffness.

F. Micro-sensors and actuators for health-related applications
------

We worked on the design, simulation, fabrication, and experiment of a novel micro-sensor that can monitoring the concentration of airborne particulate matter (PM) in real-time. We designed and simulated biomaterial-based rotary micro-motors for microfluidics applications.
