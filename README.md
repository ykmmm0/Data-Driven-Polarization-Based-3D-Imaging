# Polarization-based 3D Imaging: Paper Collection

---


## 📌 Taxonomy Overview

We categorize existing methods based on the **dominant source of constraints**, ensuring a consistent and non-overlapping classification across different paradigms.

### 🔵 Physics-based Methods

* **Advanced reflectance modeling**
* **Physically guided sensing fusion**


---

### 🟢 Data-driven Methods

* **Physics-informed Learning**
* **Learning-based Polarization 3D Imaging**
* **Multimodal Learning**

---

### 🟣 Neural Implicit Methods

* **Photometry-based polarization implicit reconstruction**
* **Geometry-based polarization implicit reconstruction**
* **Hybrid polarization implicit reconstruction**


---

📌 **Note:**
Some methods may involve multiple cues (e.g., reflectance + geometry), but each method is categorized according to its **dominant modeling principle** to avoid ambiguity.



# 🔵 1. Physics-based Methods

## 1.1 Advanced reflectance modeling

* Rahmann, S.
  *Reconstruction of Specular Surfaces Using Polarization Imaging.*
  CVPR, 2001.
  [Paper](https://ieeexplore.ieee.org/document/990468) | [Code]

* Miyazaki, T.
  *Polarization-based Inverse Rendering from a Single View.*
  ICCV, 2003.
  [Paper](https://ieeexplore.ieee.org/document/1238455) | [Code]

* Cui, Z.
  *Polarimetric Multi-View Stereo.*
  CVPR, 2017.
  [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Cui_Polarimetric_Multi-View_Stereo_CVPR_2017_paper.html) | [Code]

* Taamazyan, V.
  *Shape from Mixed Polarization.*
  Computer Optics, 2018.
  [Paper](https://arxiv.org/abs/1605.02066) | [Code]

---

### Micro-scale reflection modeling

* Ichikawa, T.
  *Fresnel microfacet BRDF: Unification of polari-radiometric surface-body reflection.*
  CVPR, 2023.
  [Paper](https://arxiv.org/abs/2212.04483) | [Code]

* Mao, Y.
  *3D Surface Reconstruction Method for Microsamples Based on Polarization Modulation Microscopy.*
  IEEE Photonics Journal, 2023.
  [Paper](https://ieeexplore.ieee.org/document/9939078) | [Code]



* McKenna, L.
  *Demonstrating unambiguous shape from polarization for Mueller imaging.*
  Optics Express, 2025.
  [Paper]([https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-14-30418](https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-14-30418)) | [Code]



* Hwang, I.
  *Sparse Ellipsometry: Portable Acquisition of Polarimetric SVBRDF and Shape.*
  ACM TOG, 2022.
  [Paper](https://arxiv.org/abs/2207.04236) | [Code]

  

---

## Photometric-constrained Modeling

* Ichikawa, T.
  *Shape from Sky: Polarimetric Normal Recovery Under Natural Illumination.*
  CVPR, 2021.
  [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Ichikawa_Shape_From_Sky_CVPR_2021_paper.html) | [Code]

* Li, X.
  *Near-infrared monocular 3D computational polarization imaging of surfaces exhibiting nonuniform reflectance.*
  Optics Express, 2021.
  [Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-10-15616) | [Code]

* Han, P.
  *Computational polarization 3D: New solution for monocular shape recovery in natural conditions.*
  Optics and Lasers in Engineering, 2022.
  [Paper](https://doi.org/10.1016/j.optlaseng.2021.106925) | [Code]




---

## Geometric-prior Modeling

* Han, P.
  *Accurate Passive 3D Polarization Face Reconstruction under Complex Conditions Assisted with Deep Learning.*
  Photonics, 2022.
  [Paper](https://www.mdpi.com/2304-6732/9/12/924) | [Code]

* Cai, Y.
  *Enhancing polarization 3D facial imaging: overcoming azimuth ambiguity without extra depth devices.*
  Optics Express, 2023.
  [Paper]([https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-26-43891](https://doi.org/10.1364/OE.505074)) | [Code]

* Azinović, D.
  *High-Resolution Facial Appearance Capture from Polarized Smartphone Images.*
  CVPR, 2023.
  [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Azinovic_High-Resolution_Facial_Appearance_Capture_From_Polarized_Smartphone_Images_CVPR_2023_paper.html) | [Code]

* Li, X.
  *Monocular polarized three-dimensional absolute depth reconstruction technology for multi-target scenes.*
  Applied Optics, 2023.
  [Paper](https://doi.org/10.1364/AO.490003) | [Code]


* Ngo, T.
  *Surface Normals and Light Directions From Shading and Polarization.*
  TPAMI, 2021.
  [Paper](https://ieeexplore.ieee.org/abstract/document/9403910) | [Code]


---

## 1.2 Physically guided sensing fusion

### Active

* Lu, J.
  *Mirror Surface Reconstruction Using Polarization Field.*
  ICCP, 2019.
  [Paper](https://ieeexplore.ieee.org/document/8747335) | [Code]

* Ding, Y.
  *Polar-Photometric Stereo Under Natural Illumination.*
  3DV, 2022.
  [Paper](https://ieeexplore.ieee.org/document/10044442) | [Code]

* Liu, R.
  *Fusion-based High-quality Polarization 3D Reconstruction.*
  Optics and Lasers in Engineering, 2023.
  [Paper](https://www.sciencedirect.com/science/article/pii/S014381662200447X) | [Code]

* Shen, Z.
  *Extended monocular 3D imaging via the fusion of diffraction-and polarization-based depth cues.*
  Optica, 2025.
  [Paper](https://doi.org/10.1364/OPTICA.560166) | [Code]

* Wang, J.
  *3D imaging of complex specular surfaces by fusing polarimetric and deflectometric information*
  Optica, 2025.
  [Paper]([https://opg.optica.org/optica/fulltext.cfm?uri=optica-12-4-446](https://doi.org/10.1364/OPTICA.538331)) | [Code]

---

### Passive

* Fukao, Y.
  *Polarimetric Normal Stereo.*
  CVPR, 2021.
  [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Fukao_Polarimetric_Normal_Stereo_CVPR_2021_paper.html) | [Code]

* Tian, X.
  *High quality 3D reconstruction based on fusion of polarization imaging and binocular stereo vision*
  Information Fusion, 2022.
  [Paper](https://doi.org/10.1016/j.inffus.2021.07.002) | [Code]

* Ding, Y.
  *Polarimetric Helmholtz Stereopsis.*
  TPAMI, 2024.
  [Paper](openaccess.thecvf.com/content/ICCV2021/html/Ding_Polarimetric_Helmholtz_Stereopsis_ICCV_2021_paper.html) | [Code]| [Data](https://polarhs.github.io/)

* Chen, G.
  *Perspective Phase Angle Model for Polarimetric 3D Reconstruction.*
  ECCV, 2022.
  [Paper](https://link.springer.com/chapter/10.1007/978-3-031-20086-1_23) | [Code]

---

# 🟢 2. Data-driven Methods

## 2.1 Physics-informed Learning

### Normal-prior-guided learning 

* Ba, Y.  *Deep Shape from Polarization.*    ECCV, 2020.    [Paper](https://link.springer.com/chapter/10.1007/978-3-030-58586-0_33) | [Code](https://github.com/UCLA-VMG/DeepSfP)

* *Wu, X.  *Three Dimensional Shape Reconstruction via Polarization Imaging and Deep Learning.*    Sensors, 2023.    [Paper](https://www.mdpi.com/1424-8220/23/10/4592) | [Code]

* Zou, S. 
  *3D Human Shape Reconstruction from a Polarization Image.*    ECCV, 2020.    [Paper](https://arxiv.org/abs/2007.09268) | [Code]
  
* Zou, S.  *Human Pose and Shape Estimation from Polarization Images.*    IEEE TMM, 2023.    [Paper](https://ieeexplore.ieee.org/document/10006144) | [Code](https://github.com/JimmyZou/PolarHumanPoseShape)

### Physically-constrained learning methods

* Deschaintre, V.  *Deep Polarization Imaging for 3D Shape and SVBRDF Acquisition.*    CVPR, 2021.    [Paper](https://ieeexplore.ieee.org/document/9578508) | [Code]

* Blanchon, M.   *P2D: A Self-supervised Method for Depth Estimation from Polarimetry.*    ICPR, 2021.    [Paper](https://arxiv.org/pdf/2007.07567) | [Code]

* Shao, M.  *Transparent Shape from a Single View Polarization Image.*    ICCV, 2023.  [Paper](https://arxiv.org/abs/2204.06331) | [Code](https://github.com/shaomq2187/TransSfP)

* Wang, B.   *Shape from Polarization via a Physical Prior-based Deep Fusion Network with Ambiguous Surface Normals.*    Optics Express, 2025.    [Paper](https://opg.optica.org/oe/viewmedia.cfm?uri=oe-33-14-29255&html=true) | [Code](https://github.com/singobl/CGA-Transformer)

* Liu, R.    *Physical prior-guided deep fusion network with shading cues for shape from polarization.*    Information Fusion, 2025.    [Paper](https://www.sciencedirect.com/science/article/pii/S1566253524005839) | [Code](https://github.com/Andray1017/SfPSNet)

* Guo, H.    *SfPUEL: Shape from Polarization under Unknown Environment Light.*    NeurIPS, 2024.    [Paper](https://neurips.cc/media/neurips-2024/Slides/93377.pdf) | [Code](https://github.com/YouweiLyu/SfPUEL)

---

## 2.2 Learning-based Polarization 3D Imaging

### 🔹 Architecture-driven

* Lei, C.    *Shape from Polarization for Complex Scenes in the Wild.*    CVPR, 2022.    [Paper](https://arxiv.org/abs/2112.11377) | [Code](https://arxiv.org/abs/2112.11377)

* Huang, T.    *Learning Accurate 3D Shape Based on Stereo Polarimetric Imaging.*    CVPR, 2023.    [Paper](https://ieeexplore.ieee.org/document/10203426) | [Code]

* Peng, Y.    *Multi-receptive Field Interaction Network for Shape from Polarization.*    SCIENCE CHINA Information Sciences, 2025.    [Paper](https://link.springer.com/article/10.1007/s11432-024-4212-2) | [Code]

* Wu, X.    *Deep Learning-based Polarization 3D Imaging Method for Underwater Targets.*    Optics Express, 2025.    [Paper](https://doi.org/10.1364/OE.541298) | [Code]

* Li, K.  *SfP-underwater: Attention-based Shape from Polarization for Underwater Scattering Environments.*    Optics and Laser Technology, 2025.    [Paper](https://www.sciencedirect.com/science/article/pii/S0030399225011363) | [Code]

---

###  Multi-stage Learning

* Li, X.    *Multi-target Distortion Correction in 3D Shape from Polarization Using Deep Neural Networks.*    Optics Letters, 2023.    [Paper](https://doi.org/10.1364/OL.499161) | [Code]

* Li, C.  *Deep Polarization Cues for Single-shot Shape and Subsurface Scattering Estimation.*    ECCV (arXiv), 2024.    [Paper](https://arxiv.org/abs/2407.08149) | [Code](https://github.com/ligoudaner377/polarized_inverse_scattering)

---

## 2.3 Multimodal Learning

* Tian, C.    *DPS-Net: Deep Polarimetric Stereo Depth Estimation.*    ICCV, 2023.    [Paper](https://ieeexplore.ieee.org/document/10377108) | [Code](https://github.com/Ethereal-Tian/DPS-Net)

* Muglikar, M.  *Event-based Shape from Polarization.*    CVPR, 2023.  [Paper](https://arxiv.org/abs/2301.06855) | [Code](https://github.com/uzh-rpg/ESfP)

* Ikemura, K.   *Robust Depth Enhancement via Polarization Prompt Fusion Tuning.*    arXiv, 2024.    [Paper](https://lastbasket.github.io/PPFT/) | [Code](https://lastbasket.github.io/PPFT/)

* Scheuble, D.    *Polarization Wavefront Lidar: Learning Large Scene Reconstruction from Polarized Wavefronts.*    CVPR, 2024.    [Paper](https://ieeexplore.ieee.org/document/10654846) | [Code](https://github.com/princeton-computational-imaging/PolLidar)

* Tian, X.    *High Quality 3D Reconstruction Based on Fusion of Polarization Imaging and Binocular Stereo Vision.*    Information Fusion, 2022.    [Paper](https://www.sciencedirect.com/science/article/pii/S1566253521001421) | [Code]
  
---


# 🟣 3. Neural Implicit Reconstruction


## 3.1 Photometry-based polarization implicit reconstruction

* Dave, A.
  *PANDORA: Polarization-Aided Neural Decomposition of Radiance.*
  ECCV, 2022.
  [Paper](https://arxiv.org/abs/2203.13458) | [Code](https://github.com/akshatdave/pandora)


  * Li, C.
  *NeISF: Neural Incident Stokes Field for Geometry and Material Estimation.*
  CVPR, 2024.
  [Paper](https://arxiv.org/abs/2311.13187) | [Code](https://github.com/sony/NeISF)


* Wu, B.
  *Glossy Object Reconstruction with Cost-effective Polarized Acquisition.*
  CVPR, 2025.
  [Paper](https://arxiv.org/abs/2504.07025) | [Code]


* Shao, M.
  *Polarimetric Inverse Rendering for Transparent Shapes Reconstruction.*
  IEEE Transactions on Multimedia, 2024.
  [Paper](https://ieeexplore.ieee.org/abstract/document/10454013) | [Code](https://github.com/shaomq2187/TransPIR)


## 3.2 Geometry-based polarization implicit reconstruction



* Chen, G.
  *PISR: Polarimetric Neural Implicit Surface Reconstruction.*
  ECCV, 2024.
  [Paper](PISR: Polarimetric Neural Implicit Surface Reconstruction.) | [Code](https://github.com/GCChen97/PISR)


* Cao, X.
  *Multi-view azimuth stereo via tangent space consistency.*
  CVPR, 2023.
  [Paper](https://arxiv.org/abs/2303.16447) | [Code](https://github.com/xucao-42/mvas)
  


* Li, Y.
  *GNeRP: Gaussian-guided Neural Reconstruction of Reflective Objects.*
  ICLR, 2024.
  [Paper](https://arxiv.org/abs/2403.11899) | [Code](https://github.com/yukiumi13/GNeRP)


* Cao, J.
  *NeRF-based polarimetric multi-view stereo.*
  Pattern Recognition, 2025.
  [Paper](https://www.sciencedirect.com/science/article/pii/S0031320324007878) | [Code]


## 3.3 Hybrid polarization implicit reconstruction
  

* Han, Y.
  *NeRSP: Neural 3D Reconstruction for Reflective Objects with Sparse Polarization.*
  CVPR, 2024.
  [Paper](https://arxiv.org/abs/2406.07111) | [Code](https://github.com/PRIS-CV/NeRSP)





* Li, C.
  *NeISF++: Neural Incident Stokes Field for Polarized Inverse Rendering.*
  2025.
  [Paper](https://arxiv.org/abs/2411.10189) | [Code](https://github.com/sony/NeISFpp)

  


---
