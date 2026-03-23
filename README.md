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

* **Neural implicit reconstruction**
  Uses implicit neural representations (e.g., NeRF/SDF) for joint geometry and appearance reconstruction

---

📌 **Note:**
Some methods may involve multiple cues (e.g., reflectance + geometry), but each method is categorized according to its **dominant modeling principle** to avoid ambiguity.



# 🔵 1. Physics-based Methods

## 1.1 Advanced reflectance modeling

* Rahmann, S.
  *Reconstruction of Specular Surfaces Using Polarization Imaging.*
  CVPR, 2001.
  [Paper](https://ieeexplore.ieee.org/document/990546) | [Code]

* Miyazaki, T.
  *Polarization-based Inverse Rendering from a Single View.*
  ICCV, 2003.
  [Paper](https://ieeexplore.ieee.org/document/1238663) | [Code]

* Cui, Z.
  *Polarimetric Multi-View Stereo.*
  CVPR, 2017.
  [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Cui_Polarimetric_Multi-View_Stereo_CVPR_2017_paper.html) | [Code]

* Taamazyan, V.
  *Shape from Mixed Polarization.*
  Computer Optics, 2018.
  [Paper](https://arxiv.org/abs/1803.09712) | [Code]

---

### Micro-scale / BRDF

* Zou, Y.
  *Developmental Trends in the Application and Measurement of BRDF.*
  Sensors, 2022.
  [Paper](https://www.mdpi.com/1424-8220/22/5/1739) | [Code]

* Xian, C.
  *Delving into High-quality SVBRDF Acquisition: A New Setup and Method.*
  Computational Visual Media, 2024.
  [Paper](https://link.springer.com/article/10.1007/s41095-024-0401-2) | [Code]

* Yang, P.
  *Polarimetric BRDF Empirical Model Considering Diffuse Reflection.*
  Chinese Journal of Physics, 2025.
  [Paper] | [Code]

* Shi, H.
  *Analysis of Infrared Polarization Properties of Rough Surfaces.*
  Optics and Laser Technology, 2022.
  [Paper](https://www.sciencedirect.com/science/article/pii/S0030399222002376) | [Code]

* Ichikawa, T.
  *Fresnel Microfacet BRDF: Unification of Polari-Radiometric Reflection.*
  CVPR, 2023.
  [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Ichikawa_Fresnel_Microfacet_BRDF_CVPR_2023_paper.html) | [Code]

* Mao, Y.
  *3D Surface Reconstruction Based on Polarization Modulation Microscopy.*
  IEEE Photonics Journal, 2023.
  [Paper](https://ieeexplore.ieee.org/document/10041441) | [Code]

* McKenna, L.
  *Unambiguous Shape from Polarization for Mueller Imaging.*
  Optics Express, 2025.
  [Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-14-30418) | [Code]

* Hwang, I.
  *Sparse Ellipsometry: Portable Acquisition of Polarimetric SVBRDF and Shape.*
  ACM TOG, 2022.
  [Paper](https://dl.acm.org/doi/10.1145/3528223.3530106) | [Code]

---

## Photometric-constrained Modeling

* Ichikawa, T.
  *Shape from Sky: Polarimetric Normal Recovery Under Natural Illumination.*
  CVPR, 2021.
  [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Ichikawa_Shape_From_Sky_CVPR_2021_paper.html) | [Code]

* Li, X.
  *Near-Infrared Monocular 3D Polarization Imaging for Nonuniform Reflectance.*
  Optics Express, 2021.
  [Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-10-15616) | [Code]

* Han, P.
  *Computational Polarization 3D Imaging in Natural Conditions.*
  Optics and Lasers in Engineering, 2022.
  [Paper](https://www.sciencedirect.com/science/article/pii/S0143816622000715) | [Code]

* Ngo, T.
  *Surface Normals and Light Directions from Shading and Polarization.*
  TPAMI, 2021.
  [Paper](https://ieeexplore.ieee.org/document/9191173) | [Code]

* Lei, C.
  *Shape from Polarization for Complex Scenes in the Wild.*
  CVPR, 2022.
  [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Lei_Shape_From_Polarization_for_Complex_Scenes_in_the_Wild_CVPR_2022_paper.html) | [Code]

---

## Geometric-prior Modeling

* Han, P.
  *Accurate Passive 3D Polarization Face Reconstruction Under Complex Conditions.*
  Photonics, 2022.
  [Paper](https://www.mdpi.com/2304-6732/9/12/924) | [Code]

* Cai, Y.
  *Enhancing Polarization 3D Facial Imaging: Overcoming Azimuth Ambiguity.*
  Optics Express, 2023.
  [Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-26-43891) | [Code]

* Azinović, D.
  *High-Resolution Facial Appearance Capture from Polarized Smartphone Images.*
  CVPR, 2023.
  [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Azinovic_High-Resolution_Facial_Appearance_Capture_From_Polarized_Smartphone_Images_CVPR_2023_paper.html) | [Code]

* Li, X.
  *Monocular Polarized 3D Absolute Depth Reconstruction Technology.*
  Applied Optics, 2023.
  [Paper](https://opg.optica.org/ao/fulltext.cfm?uri=ao-62-21-5627) | [Code]

---

## 1.2 Physically guided sensing fusion

### Active

* Lu, J.
  *Mirror Surface Reconstruction Using Polarization Field.*
  ICCP, 2019.
  [Paper](https://ieeexplore.ieee.org/document/8792177) | [Code]

* Ding, Y.
  *Polar-Photometric Stereo Under Natural Illumination.*
  3DV, 2022.
  [Paper](https://ieeexplore.ieee.org/document/10044059) | [Code]

* Liu, R.
  *Fusion-based High-quality Polarization 3D Reconstruction.*
  Optics and Lasers in Engineering, 2023.
  [Paper](https://www.sciencedirect.com/science/article/pii/S0143816622003170) | [Code]

* Shen, Z.
  *Extended Monocular 3D Imaging via Diffraction and Polarization Fusion.*
  Optica, 2025.
  [Paper](https://opg.optica.org/optica/fulltext.cfm?uri=optica-12-6-872) | [Code]

* Wang, J.
  *3D Imaging of Complex Specular Surfaces by Polarimetric Fusion.*
  Optica, 2025.
  [Paper](https://opg.optica.org/optica/fulltext.cfm?uri=optica-12-4-446) | [Code]

---

### Passive

* Fukao, Y.
  *Polarimetric Normal Stereo.*
  CVPR, 2021.
  [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Fukao_Polarimetric_Normal_Stereo_CVPR_2021_paper.html) | [Code]

* Tian, X.
  *High-quality 3D Reconstruction via Polarization and Stereo Fusion.*
  Information Fusion, 2022.
  [Paper](https://www.sciencedirect.com/science/article/pii/S156625352100176X) | [Code]

* Ding, Y.
  *Polarimetric Helmholtz Stereopsis.*
  TPAMI, 2024.
  [Paper](https://ieeexplore.ieee.org/document/10304320) | [Code]

* Chen, G.
  *Perspective Phase Angle Model for Polarimetric 3D Reconstruction.*
  ECCV, 2022.
  [Paper](https://link.springer.com/chapter/10.1007/978-3-031-20062-5_23) | [Code]

---

# 🟢 2. Data-driven Methods

## 2.1 Physics-informed Learning

* Ba, Y.  
  *Deep Shape from Polarization.*  
  ECCV, 2020.  
  [Paper](https://arxiv.org/abs/2007.10824) | [Code](https://github.com/ba-ying/deepsfp)

* *Wu, X.
  *Three Dimensional Shape Reconstruction via Polarization Imaging and Deep Learning.*  
  Sensors, 2023.  
  [Paper](https://www.mdpi.com/1424-8220/23/10/4592) | [Code]

* Zou, S. 
  *3D Human Shape Reconstruction from a Polarization Image.*  
  ECCV, 2020.  
  [Paper](https://arxiv.org/abs/2008.02068) | [Code]

* Zou, S.
  *Human Pose and Shape Estimation from Polarization Images.*  
  IEEE TMM, 2023.  
  [Paper](https://ieeexplore.ieee.org/document/10006144) | [Code]

* Deschaintre, V.  
  *Deep Polarization Imaging for 3D Shape and SVBRDF Acquisition.*  
  CVPR, 2021.  
  [Paper](https://arxiv.org/abs/2104.00674) | [Code]

* Blanchon, M. 
  *P2D: A Self-supervised Method for Depth Estimation from Polarimetry.*  
  ICPR, 2021.  
  [Paper](https://arxiv.org/abs/2011.13239) | [Code]

* Shao, M. 
  *Transparent Shape from a Single View Polarization Image.*  
  ICCV, 2023.  
  [Paper] | [Code]

* Wang, B. 
  *Shape from Polarization via a Physical Prior-based Deep Fusion Network with Ambiguous Surface Normals.*  
  Optics Express, 2025.  
  [Paper] | [Code]

* Liu, R.  
  *Fusion-based High-quality Polarization 3D Reconstruction.*  
  Optics and Lasers in Engineering, 2023.  
  [Paper] | [Code]

* Guo, H.  
  *SfPUEL: Shape from Polarization under Unknown Environment Light.*  
  NeurIPS, 2024.  
  [Paper] | [Code]

---

## 2.2 Learning-based Polarization 3D Imaging

### 🔹 Architecture-driven

* Lei, C.  
  *Shape from Polarization for Complex Scenes in the Wild.*  
  CVPR, 2022.  
  [Paper](https://arxiv.org/abs/2203.03960) | [Code]

* Huang, T.  
  *Learning Accurate 3D Shape Based on Stereo Polarimetric Imaging.*  
  CVPR, 2023.  
  [Paper] | [Code]

* Peng, Y.  
  *Multi-receptive Field Interaction Network for Shape from Polarization.*  
  SCIENCE CHINA Information Sciences, 2025.  
  [Paper] | [Code]

* Wu, X.  
  *Deep Learning-based Polarization 3D Imaging Method for Underwater Targets.*  
  Optics Express, 2025.  
  [Paper] | [Code]

* Li, K.
  *SfP-underwater: Attention-based Shape from Polarization for Underwater Scattering Environments.*  
  Optics and Laser Technology, 2025.  
  [Paper] | [Code]

---

### 🔹 Multi-stage Learning

* Li, X.  
  *Multi-target Distortion Correction in 3D Shape from Polarization Using Deep Neural Networks.*  
  Optics Letters, 2023.  
  [Paper] | [Code]

* Li, C.  
  *Deep Polarization Cues for Single-shot Shape and Subsurface Scattering Estimation.*  
  ECCV (arXiv), 2024.  
  [Paper](https://arxiv.org/abs/2407.08149) | [Code]

---

## 2.3 Multimodal Learning

* Tian, C.  
  *DPS-Net: Deep Polarimetric Stereo Depth Estimation.*  
  ICCV, 2023.  
  [Paper] | [Code]

* Muglikar, M.
  *Event-based Shape from Polarization.*  
  CVPR, 2023.  
  [Paper](https://arxiv.org/abs/2301.06855) | [Code]

* Ikemura, K.  
  *Robust Depth Enhancement via Polarization Prompt Fusion Tuning.*  
  arXiv, 2024.  
  [Paper](https://arxiv.org/abs/2404.04318) | [Code]

* Scheuble, D.  
  *Polarization Wavefront LiDAR.*  
  CVPR, 2024.  
  [Paper] | [Code]

* Tian, X.  
  *High Quality 3D Reconstruction Based on Fusion of Polarization Imaging and Binocular Stereo Vision.*  
  Information Fusion, 2022.  
  [Paper] | [Code]
  
---


# 🟣 3. Neural Implicit Reconstruction


* Dave, A.
  *PANDORA: Polarization-Aided Neural Decomposition of Radiance.*
  ECCV, 2022.
  [Paper](https://arxiv.org/abs/2203.13458) | [Code]

* Liu, Y.
  *NeRO: Neural Geometry and BRDF Reconstruction of Reflective Objects.*
  ACM TOG, 2023.
  [Paper](https://arxiv.org/abs/2304.13634) | [Code]

* Han, Y.
  *NeRSP: Neural 3D Reconstruction for Reflective Objects with Sparse Polarization.*
  CVPR, 2024.
  [Paper](https://arxiv.org/abs/2406.07111) | [Code](https://github.com/PRIS-CV/NeRSP)

* Chen, G.
  *PISR: Polarimetric Neural Implicit Surface Reconstruction.*
  ECCV, 2024.
  [Paper] | [Code]

* Li, C.
  *NeISF: Neural Incident Stokes Field for Geometry and Material Estimation.*
  CVPR, 2024.
  [Paper](https://arxiv.org/abs/2311.13187) | [Code]

* Li, C.
  *NeISF++: Neural Incident Stokes Field for Polarized Inverse Rendering.*
  2025.
  [Paper](https://arxiv.org/abs/2411.10189) | [Code]

* Li, Y.
  *GNeRP: Gaussian-guided Neural Reconstruction of Reflective Objects.*
  ICLR, 2024.
  [Paper](https://arxiv.org/abs/2403.11899) | [Code]

* Ge, W.
  *Ref-NeuS: Neural Implicit Surface Learning with Reflection.*
  ICCV, 2023.
  [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Ge_Ref-NeuS_ICCV_2023_paper.html) | [Code]

---


---
