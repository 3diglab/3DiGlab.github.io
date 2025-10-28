---
title: Efficient Shape Matching via JPEG-Based Compression of Correspondence Matrices
contact_name: Simone Melzi
contact_email: simone.melzi@unimib.it
date: 2025-10-01 00:00:00-0000
assigned: false
#image: 3DiG.png # uncomment to show the image from assets/img/
---
This thesis explores the use of image compression techniques, specifically JPEG, to reduce the dimensionality of matrices representing correspondences between 3D shapes. Shape matching problems often rely on large-scale matrices, such as point-to-point correspondence maps or functional maps, which can be computationally expensive to store and optimize. By interpreting these matrices as images and compressing them using JPEG, we aim to significantly reduce the number of variables in the optimization problem, while maintaining the accuracy and quality of the resulting correspondences. The approach will be evaluated both on complete correspondence matrices and on alternative matrix representations, such as functional maps.

#### Data

Standard 3D shape matching benchmarks, including FAUST, SCAPE, TOSCA, and SMAL.
SHREC 2019 and SHREC 2020 datasets, commonly used for evaluating shape correspondence methods.

#### Expected Outcomes

- An implementation of a JPEG-based compression pipeline for correspondence matrices.
- A systematic comparison of optimization performance with and without matrix compression under identical settings.
- Quantitative evaluation of efficiency (memory usage, runtime) and correspondence quality (accuracy, stability).
- Insights into the trade-off between compression ratio and optimization reliability across different datasets and correspondence representations.

#### References (State of the Art)

- Ovsjanikov et al., Functional Maps: A Flexible Representation of Maps Between Shapes, SIGGRAPH 2012.
- Melzi et al., SHREC 2019: Matching Humans with Different Connectivity, Computers \& Graphics 2019.
