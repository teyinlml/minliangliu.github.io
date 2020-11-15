---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

A. Machine learning applications in biomechanics
------

A1. A machine learning approach to investigate the relationship between shape features and numerically predicted risk of ascending aortic aneurysm.
* We investigated the feasibility of a machine learning approach to establish the linkages between shape features and FEA-predicted ascending thoracic aortic aneurysm (ATAA) rupture risk, and it may serve as a faster surrogate for FEA associated with long simulation time and numerical convergence issues. The results show that statistical shape model (SSM) parameters can be used as strong shape features to make predictions of risk scores consistent with FEA. Compared to FEA, this machine learning approach is magnitudes faster.

<p align="center">
  <img src="https://minliangliu.github.io//images/PRR.PNG" width="436" height="351" />
</p>

* L. Liang, **M. Liu (Co-first Author)**, C. Martin, J.A. Elefteriades, and W. Sun. 2017. *Biomechanics and Modeling in Mechanobiology*. [[Link](https://link.springer.com/article/10.1007/s10237-017-0903-9)]

A2. A deep learning approach to estimate tissue nonlinear anisotropic stress-strain responses from microscopy images.
* L. Liang, **M. Liu**, and W. Sun. 2017. *Acta Biomaterialia*. [[Link](https://www.sciencedirect.com/science/article/pii/S1742706117305883)]

A3. A deep learning approach to estimate stress distribution: a fast and accurate surrogate of finite-element analysis.
* L. Liang, **M. Liu**, C. Martin, and W. Sun. 2018. *Journal of The Royal Society Interface*. [[Link](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2017.0844)]

A4. A machine learning approach to estimate the zero‐pressure geometry of human thoracic aorta.
* L. Liang, **M. Liu**, C. Martin, and W. Sun. 2018. *International Journal for Numerical Methods in Biomedical Engineering*. [[Link](https://onlinelibrary.wiley.com/doi/abs/10.1002/cnm.3103)]

A5. A machine learning approach for estimation of *in vivo* constitutive parameters of the aortic wall.
* We developed a machine learning approach to expedite the procedure of *in vivo* material parameter identification. The nonlinear relationship between the two loaded shapes and the constitutive parameters is established by an ML-model, which was trained and tested using finite element (FE) simulation datasets.

<p align="center">
<img src="https://minliangliu.github.io//images/MLmat.PNG" width="507" height="189" />
</p>
 
* **M. Liu**, L. Liang, and W. Sun. 2019. *Computer Methods in Applied Mechanics and Engineering*. [[Link](https://www.sciencedirect.com/science/article/pii/S0045782518306297)]

A6. A physics-informed neural network for constitutive modeling of soft biological tissues.
* We developed a novel generic physics-informed neural network material (NNMat) model which employs a hierarchical learning strategy and a novel neural network structure: (1) a class parameter set for characterizing the general elastic properties; and (2) a subject parameter set (three parameters) for describing individual material response. The trained NNMat model may be directly adopted for a different subject without re-training the class parameters, and only the subject parameters are considered as constitutive parameters. Skip connections are utilized in the neural network to facilitate hierarchical learning. A convexity constraint was imposed to the NNMat model to ensure that the constitutive model is physically relevant.

<p align="center">
<img src="https://minliangliu.github.io//images/NNMat.PNG" width="581" height="344" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2020. *Computer Methods in Applied Mechanics and Engineering*. [[Link](https://www.sciencedirect.com/science/article/pii/S0045782520305879)]

B. Inverse methods for identification of *in vivo* hyperleastic properties of the aortic wall
------

B1. A multi-resolution direction search (MRDS) approach based on finite element updating scheme.
* We proposed a novel MRDS approach for estimation of nonlinear anisotropic constitutive parameters of the aortic wall. Based on the finite element (FE) updating scheme, the MRDS approach searches the discretized principal component analysis (PCA) spaces at different resolutions in a ‘coarse to fine’ fashion. Our results show that the number of FE iterations was significantly reduced compared to previous methods.

<p align="center">
<img src="https://minliangliu.github.io//images/multi.PNG" width="650" height="386" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2018. *Journal of the Mechanical Behavior of Biomedical Materials*. [[Link](https://www.sciencedirect.com/science/article/pii/S1751616117304502)]

B2. Transmural mean stress of the aortic wall can be obtained without patient-specific material properties and residual deformations.
* We demonstrated that the transmural mean stress can be readily obtained from *in vivo* clinical images without knowing the patient-specific material properties and residual deformations. Computation of patient-specific mean stress can be greatly simplified by using statical determinacy, which may be clinically valuable.

<p align="center">
<img src="https://minliangliu.github.io//images/SD.PNG" width="725" height="246" />
</p>

* **M. Liu**, L. Liang, C. Martin, and W. Sun. 2018. *Biomechanics and Modeling in Mechanobiology*. [[Link](https://link.springer.com/article/10.1007/s10237-018-1089-5)]

B3. A novel inverse method based on a stress-matching objective function.
* We developed a novel inverse method based on a stress-matching strategy. The computationally-expensive FE simulations can be avoided. The method was validated through numerical experiments by using the *in vivo* data from 4 ATAA patients. The results demonstrated that the method is computationally efficient.

<p align="center">
<img src="https://minliangliu.github.io//images/stress.PNG" width="639" height="273" />
</p>

* **M. Liu**, L. Liang, and W. Sun. 2017. *Journal of the Mechanical Behavior of Biomedical Materials*. [[Link](https://www.sciencedirect.com/science/article/pii/S1751616117301893)]

B4. Comparison of *in vivo*-identified (from CT images) vs *ex vivo*-fitted (from tissue testing) hyperelastic properties.
* Using an improved version of MRDS approach, we estimated *in vivo* aortic tissue hyperelastic properties of two ATAA patients from pre-operative gated CT scans. For comparison, corresponding surgically-resected aortic wall tissue samples were obtained and subjected to planar biaxial tests. Relatively close matches were achieved for the *in vivo*-identified and *ex vivo*-fitted stress-stretch responses.

<p align="center">
<img src="https://minliangliu.github.io//images/validation.PNG" width="873" height="358" />
</p>

* **M. Liu**, L. Liang, F. Sulejmani, X. Lou, G. Iannucci, E. Chen, B. Leshnower, and W. Sun. 2019. *Scientific Reports*. [[Link](https://www.nature.com/articles/s41598-019-49438-w)]

C. Anisotropic failure criteria and probabilistic failure metric of the aortic wall
------

C1. A novel anisotropic failure criterion with distributed fiber orientations.
* We proposed a novel stress-based anisotropic failure criterion with dispersed fiber orientations. In the new failure criterion, the overall failure metric is computed by using angular integration (AI) of failure metrics in all directions. Affine rotations of fiber orientations due to finite deformation are taken into account in an anisotropic hyperelastic constitutive model.

<p align="center">
<img src="https://minliangliu.github.io//images/failure.PNG" width="637" height="248" />
</p>

* **M. Liu**, H. Dong, X. Lou, G. Iannucci, E.P. Chen, B.G. Leshnower, and W. Sun. 2020. *Journal of Biomechanical Engineering*. [[Link](https://asmedigitalcollection.asme.org/biomechanical/article/142/11/111002/1086084/A-Novel-Anisotropic-Failure-Criterion-With)]

C2. A probabilistic and anisotropic failure metric based on the Tsai-Hill theory.
* We developed a novel probabilistic and anisotropic failure metric for ATAA risk assessment. Uniaxial tensile tests were performed using aortic tissue samples of 84 ATAA patients, from which a joint probability distribution of the anisotropic wall strengths was obtained. An anisotropic failure probability (FP) metric based on the Tsai-Hill (TH) failure criterion was subsequently derived. The novel FP metric, which incorporates uncertainty and anisotropy of failure properties, can be evaluated given wall stresses. For method validation, “ground-truth” risks of additional 41 ATAA patients were numerically-reconstructed using matching CT images and tissue testing data. 

<p align="center">
<img src="https://minliangliu.github.io//images/FP.PNG" width="694" height="271" />
</p>

* **M. Liu**, L. Liang, Q. Zou, Y. Ismail, X. Lou, G. Iannucci, E.P. Chen, B.G. Leshnower, J.A. Elefteriades, and W. Sun. 2020. *bioRxiv*. [[Link](https://www.biorxiv.org/content/10.1101/2020.09.28.317255v1.abstract)]

D. Modeling of time-dependent tissue property changes
------

D1. An Anisotropic volumetric growth approach for modeling of three-dimensional residual stress in the aortic wall.
* H. Liu, M. Zhang, **M. Liu**, C. Martin, Z. Cai, and W. Sun. 2019. *Journal of the Mechanical Behavior of Biomedical Materials*. [[Link](https://www.sciencedirect.com/science/article/pii/S1751616118311664)]

D2. Modeling fatigue damage of biological soft tissues using a residual stiffness-based model.
* H. Dong, **M. Liu**, C. Martin, and W. Sun. 2020. *Journal of the Mechanics and Physics of Solids*. [[Link](https://www.sciencedirect.com/science/article/pii/S0022509620303082)]

E. Micro-sensors and actuators for health-related applications
------

E1. An airborne particulate matter sensor based on 3D printed virtual impactor and quartz crystal microbalance.
* We designed and fabricated a miniature system for detection of airborne particulate matter (PM). To classify airborne particles according to their size, a virtual impactor is fabricated using three-dimensional (3D) printing process. A QCM resonant sensor is utilized to detect the mass of the separated particles. Experimental validations were performed which showed that the resonant frequency of the QCM turns downward linearly with the PM mass loading increasing.

<p align="center">
<img src="https://minliangliu.github.io//images/PM.PNG" width="445" height="328" />
</p>

* J. Zhao, **M. Liu (Co-first Author)**, L. Liang, W. Wang, and J. Xie. 2016. *Sensors and Actuators A: Physical*. [[Link](https://www.sciencedirect.com/science/article/pii/S0924424715302788)]

E2. Biobased high-performance rotary micromotors for individually reconfigurable micromachine arrays and microfluidic applications.
* K. Kim, Z. Liang, **M. Liu**, and D.E. Fan. 2017. *ACS Applied Materials & Interfaces*. [[Link](https://pubs.acs.org/doi/abs/10.1021/acsami.6b13997)]
