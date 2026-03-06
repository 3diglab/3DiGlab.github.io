---
title: "Serialization-Based Methods and Positional Encoding for 3D Point Cloud Shape Matching"
contact_name: Simone Melzi
contact_email: simone.melzi@unimib.it
date: 2026-03-06 00:00:00-0000
assigned: false
# image: 3DiG.png # uncomment to show the image from assets/img/
tags:
#     - bachelor's
    - master's
#     - computer vision
    - geometric deep learning
---
This thesis investigates serialization-based transformer methods for 3D point clouds and the role of positional encoding in shape matching and correspondence. Recent works suggest that competitive performance can be achieved with Transformer-based architectures paired with effective point serialization and positional encodings. The project will (i) reproduce and compare recent approaches, and (ii) design a well-motivated improvement (e.g., a new positional encoding variant or a hybrid serialization strategy) validated through controlled experiments.
The study will focus on correspondence robustness under typical challenges: noise, varying point density, partial shapes, and pose changes.

#### Data

Experiments will use established shape matching datasets, for example: FAUST (human shapes; mesh-to-point cloud variants), and SHREC’19 (human matching / correspondence).
Plus, point clouds will be augmented with synthetic degradations (subsampling, noise, partiality) to emulate real acquisition conditions.

#### Expected Outcomes

- A reproducible benchmark comparing serialization + positional encoding choices for point cloud correspondence.
- Clear ablation results identifying which design choices matter most (accuracy vs. efficiency).
- One validated improvement over a baseline, with code and experimental report.

#### References (State of the Art)

- Raganato, A., Pasi, G., Melzi, S. (2023). Attention and positional encoding are (almost) all you need for shape matching. Computer Graphics Forum (SGP).
- Wu, X. et al. (2024). Point Transformer V3: Simpler, Faster, Stronger. CVPR.
