# Awesome 3D Gaussian Splatting for Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **3D Gaussian Splatting papers relating to the Robotics domain**.

#### Please feel free to send me [pull requests](https://github.com/dtc111111/awesome-3dgs-for-robotics) or [email](mailto:dengtianchen@sjtu.edu.cn) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

---

## Overview
  - [3DGS Survey](#3dgs-survey)
    
  - [3DGS Foundation Model](#3dgs-general-model)

  - [Perception](#perception)
    - [Semantic](#Semantic)
    - [Multi-Modal](#MM)
    - [Object Detection](#Object-Detection)
    
  - [Mapping & Localization](#slam)
    - [3D Reconstruction](#3D-Reconstruction)
    - [Dynamic Scene Reconstruction](#Dynamic-Reconstruction)
    - [Visual-SLAM](#Visual-SLAM)
    - [Lidar-SLAM](#Lidar-SLAM)
    - [Multimodal-SLAM](#Multimodal-SLAM)
      
  - [Planning & Navigation](#planningnavigation)
  - [Manipulation & RL](#manipulationrl)

  - [Citation](#citation)

---
## 3DGS Survey

#### [S1] A Survey on 3D Gaussian Splatting
- **🧑‍🔬 Author**：Guikun Chen, Wenguan Wang
- **🏫 Institute**：Zhejiang University
- **🔗 Link**：[[arXiv:2401.03890](https://arxiv.org/abs/2401.03890)]


#### [S2] 3D Gaussian as a New Vision Era: A Survey
- **🧑‍🔬 Author**：Ben Fei, Jingyi Xu, Rui Zhang, Qingyuan Zhou, Weidong Yang, Ying He
- **🏫 Institute**：Fudan University ⟐ Nanyang Technological University
- **🔗 Link**：[[arXiv:2402.07181](https://arxiv.org/abs/2402.07181)]


#### [S3] Recent Advances in 3D Gaussian Splatting
- **🧑‍🔬 Author**：Tong Wu, Yu-Jie Yuan, Ling-Xiao Zhang, Jie Yang, Yan-Pei Cao, Ling-Qi Yan, Lin Gao
- **🏫 Institute**：Chinese Academy of Sciences ⟐ VAST ⟐  University of California
- **🔗 Link**：[[arXiv:2403.11134](https://arxiv.org/abs/2403.11134)]


#### [S4] Gaussian Splatting: 3D Reconstruction and Novel View Synthesis, a Review
- **🧑‍🔬 Author**：Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård
- **🏫 Institute**：University of Agder
- **🔗 Link**：[[arXiv:2405.03417](https://arxiv.org/abs/2405.03417)]

## 3DGS Foundation Model
* 3D Gaussian Splatting for Real-Time Radiance Field Rendering, *SIGGRAPH, 2023*. [[Paper](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf)] [[Website](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)]
* 2D Gaussian Splatting for Geometrically Accurate Radiance Fields, *SIGGRAPH, 2024*. [[Paper](https://arxiv.org/pdf/2403.17888)] [[Website](https://surfsplatting.github.io/)]  [[Code](https://github.com/hbb1/2d-gaussian-splatting)]
* **Mip-splatting**: Alias-free 3d gaussian splatting, *CVPR, 2024*. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Yu_Mip-Splatting_Alias-free_3D_Gaussian_Splatting_CVPR_2024_paper.pdf)] [[Website](https://niujinshuchong.github.io/mip-splatting/)]  [[Code](https://github.com/autonomousvision/mip-splatting)]


---
## Citation

If you find this repository useful, please consider citing this list:

```
@misc{Deng20243dgspaperlist,
    title = {awesome-Implicit-NeRF-SLAM},
    author = {Tianchen Deng, Yue Pan, Xingxing Zuo, Shenghai Yuan, Nailin Wang, Hesheng Wang, Jingchuan Wang, Cryill Stachness, Lihua Xie, Danwei Wang, Weidong Chen},
    howpublished = {\url{https://github.com/dtc111111/awesome-3dgs-for-robotics}},
    year = {2024}
}
```
