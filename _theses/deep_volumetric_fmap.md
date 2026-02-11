---
title: "Deep Learning for Volumetric Functional Maps"
contact_name: Simone Melzi
contact_email: simone.melzi@unimib.it
date: 2026-02-01 00:00:00-0000
assigned: false
# image: 3DiG.png # uncomment to show the image from assets/img/
tags:
#     - bachelor's
    - master's
#     - computer vision
    - geometric deep learning
---
This thesis aims to extend deep learning methods for shape correspondence from
surface to volumetric domains. Specifically, the project will build upon the
functional map framework, which has recently been generalized to volumetric
data through the eigenfunctions of the volumetric Laplace operator. Starting
from existing deep functional map architectures designed for surfaces, the
student will adapt and redesign the feature extraction and map estimation
pipelines to operate on tetrahedral meshes and volumetric representations.
Ultimately, the resulting methods will be evaluated on volumetric shape
matching benchmarks, comparing their accuracy against both classical
surface-based and volumetric baselines.

#### Data

Tetrahedral mesh datasets from the volumetric functional maps literature, including volumetric versions of established surface benchmarks (e.g., FAUST, SHREC).

#### Expected Outcomes

- Adaptation of deep functional map architectures to volumetric domains.
- Experimental comparison with surface-based and classical volumetric methods on shape matching tasks.
- Analysis of the benefits of volumetric spectral information for learning-based correspondence.

#### References (State of the Art)

- Donati, N., et al. (2020). Deep Geometric Functional Maps: Robust Feature Learning for Shape Correspondence. CVPR 2020. https://openaccess.thecvf.com/content_CVPR_2020/papers/Donati_Deep_Geometric_Functional_Maps_Robust_Feature_Learning_for_Shape_Correspondence_CVPR_2020_paper.pdf
- Maggioli, F., et al. (2025). Volumetric Functional Maps. arXiv. https://arxiv.org/abs/2506.13212
