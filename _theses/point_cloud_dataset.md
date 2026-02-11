---
title: "A Multi-Source Human Point Cloud Dataset for Shape Correspondence Benchmarking"
contact_name: Simone Melzi
contact_email: simone.melzi@unimib.it
date: 2026-02-01 00:00:00-0000
assigned: false
image: poit_cloud_theses.png
tags:
    - bachelor's
#     - master's
    - computer vision
#     - geometric deep learning
---
This thesis aims to build and curate a benchmark dataset of human point clouds
acquired from multiple heterogeneous sources, including high-quality meshes,
dense 3D scans, Kinect-style depth sensors, and Gaussian splats.
Specifically, all acquisitions will be registered to a common SMPL body model,
enabling the generation of ground-truth correspondences across shapes and
modalities. From this unified representation, both sparse point-to-point maps
and dense registrations will be derived, even across large pose variations and
different acquisition conditions. Ultimately, the resulting benchmark will be
used to evaluate existing point cloud shape matching algorithms, assessing
their robustness under realistic cross-source scenarios where traditional
methods are known to struggle.

#### Data

Multi-source human point clouds from existing repositories (SHREC'19, BEHAVE) and synthetic acquisitions, registered to the SMPL body model. Sources include meshes, 3D scans, synthetic scans, Kinect captures, and Gaussian splats.

#### Expected Outcomes

- A curated multi-source human point cloud dataset with consistent SMPL-based registration.
- Quantitative evaluation of existing shape matching baselines under cross-source conditions.

#### References (State of the Art)

- Melzi, S., et al. (2019). SHREC 2019: Matching Humans with Different Connectivity. Eurographics Workshop on 3D Object Retrieval.
- Loper, M., et al. (2015). SMPL: A Skinned Multi-person Linear Model. ACM Trans. Graph., 34(6).
- Bhatnagar, B.L., et al. (2022). BEHAVE: Dataset and Method for Tracking Human Object Interactions. arXiv. https://arxiv.org/abs/2204.06950
