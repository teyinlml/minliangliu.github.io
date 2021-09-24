---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

A. Machine learning surrogate models for fast computational analyses
------
We developed a series of machine learning and deep learning approaches for surrogate modeling in cardiovascular simulations, these data-driven approaches can lead to fundamental improvements in computational efficiency, i.e., obtain accurate simulation results in real-time.

A1. Predicting aneurysm rupture risk based on shape features.
* We developed a machine learning approach to predict ascending thoracic aortic aneurysm (ATAA) rupture risk based on shape features. The results show that statistical shape model (SSM) parameters can be used as strong shape features to make predictions of risk scores consistent with finite element analysis (FEA)- a classical computational approach associated with long simulation time and numerical convergence issues. The machine learning model demonstrated its capabilities to bypass FEA and directly predict the FEA results in <1 second. This was the first published study that bridged machine learning and biomechanics for surrogate modeling.

<p align="center">
  <img src="https://minliangliu.github.io//images/PRR.PNG" width="436" height="351" />
</p>

* L. Liang, **M. Liu (Co-first Author)**, C. Martin, J.A. Elefteriades, and W. Sun. 2017. *Biomechanics and Modeling in Mechanobiology*. [[Link](https://link.springer.com/article/10.1007/s10237-017-0903-9)]

A2. Computing stress distribution as a fast and accurate surrogate of finite element analysis.
* We developed a deep learning model to estimate stress distribution on the aortic wall. An FEA simulation time of 30 minutes was reduced to a mere <1 second runtime and the results were within 1% error. This study has paved the way for fast and accurate computational analysis using machine learning surrogate models.
 
* L. Liang, **M. Liu**, C. Martin, and W. Sun. 2018. *Journal of The Royal Society Interface*. [[Link](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2017.0844)]

A3. Direct identification of *in vivo* constitutive parameters from aorta geometries at two cardiac phases.
* Machine learning is more powerful for inverse problems which are traditionally solved by using iterative methods. We demonstrated the use of a machine learning model to vastly accelerate the identification of *in vivo* material parameters. The time cost of the inverse calculation was greatly reduced: from hours, days, or weeks to <1 second.

<p align="center">
<img src="https://minliangliu.github.io//images/MLmat.PNG" width="507" height="189" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2019. *Computer Methods in Applied Mechanics and Engineering*. [[Link](https://www.sciencedirect.com/science/article/pii/S0045782518306297)]

A4. Recovering the unloaded configuration of the aorta from *in vivo* loaded geometries.
* L. Liang, **M. Liu**, C. Martin, and W. Sun. 2018. *International Journal for Numerical Methods in Biomedical Engineering*. [[Link](https://onlinelibrary.wiley.com/doi/abs/10.1002/cnm.3103)]

A5. Direct computation of failure metric on the aortic wall, bypassing inverse and forward computation steps.
* **M. Liu**, L. Liang, Y. Ismail, H. Dong, X. Lou, G. Iannucci, E.P. Chen, B.G. Leshnower, J.A. Elefteriades, and W. Sun. 2021. *Computers in Biology and Medicine*. [[Link](https://www.sciencedirect.com/science/article/pii/S0010482521005886?via%3Dihub)]


B. Inverse identification of *in vivo* hyperleastic properties of the aortic wall from clinical images
------
We developed inverse methods to identify anisotropic hyperelastic material properties of the aortic wall from clinical images. The overall goal was to increase the computational efficiency towards clinical applications by employing novel inverse identification strategies. These inverse identification methods can facilitate personalized computational modeling for the diagnosis and treatment of cardiovascular diseases.

B1. A multi-resolution direction search (MRDS) approach based on finite element updating scheme.
* We proposed a novel MRDS approach for estimation of nonlinear anisotropic constitutive parameters of the aortic wall. Based on the finite element (FE) updating scheme, the MRDS approach searches the discretized principal component analysis (PCA) spaces at different resolutions in a ‘coarse to fine’ fashion. Our results show that the number of FE iterations was significantly reduced compared to previous methods.

<p align="center">
<img src="https://minliangliu.github.io//images/multi.PNG" width="650" height="386" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2018. *Journal of the Mechanical Behavior of Biomedical Materials*. [[Link](https://www.sciencedirect.com/science/article/pii/S1751616117304502)]

B2. Transmural mean stress of the aortic wall can be obtained without patient-specific material properties and residual deformations.
* We demonstrated that the transmural mean stress can be readily obtained from *in vivo* clinical images without knowing the patient-specific material properties and residual deformations. Computation of patient-specific mean stress can be greatly simplified by using statical determinacy.

<p align="center">
<img src="https://minliangliu.github.io//images/SD.PNG" width="725" height="246" />
</p>

* **M. Liu**, L. Liang, C. Martin, and W. Sun. 2018. *Biomechanics and Modeling in Mechanobiology*. [[Link](https://link.springer.com/article/10.1007/s10237-018-1089-5)]

B3. A novel inverse method based on a stress-matching objective function.
* We developed a new computationally efficient inverse method based on a stress-matching strategy. By using statical determinacy of the aorta, the material parameters can be obtained by solving a subset of the inverse probelm- the constitutive equations, without invoking the computationally-expensive FEA. The method was validated through numerical experiments by using *in vivo* image data and surgically-resected tissue samples.

<p align="center">
<img src="https://minliangliu.github.io//images/stress.PNG" width="639" height="273" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2017. *Journal of the Mechanical Behavior of Biomedical Materials*. [[Link](https://www.sciencedirect.com/science/article/pii/S1751616117301893)]

B4. Comparison of *in vivo*-identified (from CT images) vs *ex vivo*-fitted (from tissue testing) hyperelastic properties.
* Using an improved version of MRDS approach, we estimated *in vivo* hyperelastic properties of two ATAA patients from pre-operative gated CT scans. For comparison, corresponding surgically-resected aortic tissue samples were obtained and subjected to planar biaxial tests. Relatively close matches were achieved for the *in vivo*-identified and *ex vivo*-fitted stress-stretch responses.

<p align="center">
<img src="https://minliangliu.github.io//images/validation.PNG" width="873" height="358" />
</p>

* **M. Liu**, L. Liang, F. Sulejmani, X. Lou, G. Iannucci, E. Chen, B. Leshnower, and W. Sun. 2019. *Scientific Reports*. [[Link](https://www.nature.com/articles/s41598-019-49438-w)]

C. Learning soft tissue constitutive behaviors via deep neural networks
------
We established deep neural networks as an alternative to model constitutive behaviors of soft tissues. These deep neural network models incorporate physical or microstructural knowledge of soft tissues and have led to performance improvements that could not be achieved by classical constitutive models. 

C1. A generic constitutive model of soft tissues enabled by physics-informed learning.
* We developed a novel generic physics-informed neural network material (NNMat) model which employs a hierarchical learning strategy and a novel neural network structure: (1) a class parameter set for characterizing the general elastic properties; and (2) a subject parameter set (three parameters) for describing individual material response. The trained NNMat model may be directly adopted for a different subject without re-training the class parameters, and only the subject parameters are considered as constitutive parameters. Skip connections are utilized in the neural network to facilitate hierarchical learning. A convexity constraint was imposed to the NNMat model to ensure that the constitutive model is physically relevant.

<p align="center">
<img src="https://minliangliu.github.io//images/NNMat.PNG" width="581" height="344" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2020. *Computer Methods in Applied Mechanics and Engineering*. [[Link](https://www.sciencedirect.com/science/article/pii/S0045782520305879)]

C2. Estimating tissue stress-strain responses from microscopy images by using deep convolutional neural networks.
* L. Liang, **M. Liu**, and W. Sun. 2017. *Acta Biomaterialia*. [[Link](https://www.sciencedirect.com/science/article/pii/S1742706117305883)]

D. Anisotropic failure criterion and probabilistic failure metric of the aortic wall
------
We developed a fiber-based failure criterion and a probabilistic and anisotropic failure index for aortic tissues. The new failure criterion was specifically proposed to capture the ansiotropy of the failure properties. Since the wall strengths can only be accurately obtained using destructive and invasive means, we developed a probabilistic failure metric to incorporate the uncertainties of the wall strength distributions. These novel failure models can be used for noninvasive risk assessment of thoracic aortic aneurysms.

D1. A novel anisotropic failure criterion with distributed fiber orientations.
* We proposed a novel stress-based anisotropic failure criterion with dispersed fiber orientations. In the new failure criterion, the overall failure metric is computed by using angular integration (AI) of failure metrics in all directions. Affine rotations of fiber orientations due to finite deformation are taken into account in an anisotropic hyperelastic constitutive model.

<p align="center">
<img src="https://minliangliu.github.io//images/failure.PNG" width="637" height="248" />
</p>

* **M. Liu**, H. Dong, X. Lou, G. Iannucci, E.P. Chen, B.G. Leshnower, and W. Sun. 2020. *Journal of Biomechanical Engineering*. [[Link](https://asmedigitalcollection.asme.org/biomechanical/article/142/11/111002/1086084/A-Novel-Anisotropic-Failure-Criterion-With)]

D2. A probabilistic and anisotropic failure metric based on the Tsai-Hill theory.
* We developed a probabilistic and anisotropic failure metric for ATAA risk assessment. We performed uniaxial tensile failure tests using aortic tissue samples of 84 ATAA patients, from which a joint probability distribution of the anisotropic wall strengths was obtained. Subsequently, we derived an anisotropic failure probability (FP) metric based on the Tsai-Hill (TH) failure criterion. The novel FP metric demonstrated better performance than isotropic or deterministic indices in discrimination tests. 

<p align="center">
<img src="https://minliangliu.github.io//images/FP.PNG" width="694" height="271" />
</p>

* **M. Liu**, L. Liang, Q. Zou, Y. Ismail, X. Lou, G. Iannucci, E.P. Chen, B.G. Leshnower, J.A. Elefteriades, and W. Sun. 2021. *Journal of the Mechanics and Physics of Solids*. [[Link](https://www.sciencedirect.com/science/article/abs/pii/S002250962100199X?via%3Dihub)]

E. Modeling of tissue fatigue damage and growth
------

E1. Recovering three-dimensional residual stresses in the aortic wall via an anisotropic volumetric growth model.
* H. Liu, M. Zhang, **M. Liu**, C. Martin, Z. Cai, and W. Sun. 2019. *Journal of the Mechanical Behavior of Biomedical Materials*. [[Link](https://www.sciencedirect.com/science/article/pii/S1751616118311664)]

E2. Fatigue damage modeling of prosthetic heart valve tissues using a residual stiffness-based model.
* H. Dong, **M. Liu**, C. Martin, and W. Sun. 2020. *Journal of the Mechanics and Physics of Solids*. [[Link](https://www.sciencedirect.com/science/article/pii/S0022509620303082)]

F. Micro-systems for health-related applications
------

F1. A miniature airborne particulate matter sensor based on 3D printed virtual impactor and quartz crystal microbalance (QCM).
* We designed and fabricated a miniature system for detection of airborne particulate matter (PM). To classify airborne particles according to their size, a virtual impactor is fabricated using 3D printing technology. A QCM resonant sensor is utilized to detect the mass of the separated particles. Experiments proved that the miniature system can montior PM concentrations in real-time.

<p align="center">
<img src="https://minliangliu.github.io//images/PM.PNG" width="445" height="328" />
</p>

* J. Zhao, **M. Liu (Co-first Author)**, L. Liang, W. Wang, and J. Xie. 2016. *Sensors and Actuators A: Physical*. [[Link](https://www.sciencedirect.com/science/article/pii/S0924424715302788)]

F2. Biobased high-performance rotary micromotors for individually reconfigurable micromachine arrays and microfluidic applications.
* K. Kim, Z. Liang, **M. Liu**, and D.E. Fan. 2017. *ACS Applied Materials & Interfaces*. [[Link](https://pubs.acs.org/doi/abs/10.1021/acsami.6b13997)]
