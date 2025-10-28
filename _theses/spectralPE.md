---
title: Leveraging Fiedler Vector and Eigenvector Centrality for Positional Encoding in Graph and Mesh Neural Networks
contact_name: Simone Melzi
contact_email: simone.melzi@unimib.it
date: 2025-10-01 00:00:00-0000
assigned: false
# image: 3DiG.png # uncomment to show the image from assets/img/
tags:
#     - bachelor's
    - master's
#     - computer vision
    - geometric deep learning
---
This thesis investigates the application of spectral graph properties—specifically the Fiedler vector and eigenvector centrality—as positional encodings in Transformer and Graph Neural Network (GNN) architectures for graph and mesh data. The study will examine two approaches: utilizing the absolute values of the Fiedler vector as features and employing it to order vertices, thereby defining a canonical node sequence. Additionally, eigenvector centrality will be explored as an alternative positional encoding method.

#### Data

Standard graph and mesh datasets from the literature, such as FAUST and ShapeNet for 3D meshes, and benchmark graph datasets like Cora and PubMed for general graph experiments.

#### Expected Outcomes

- Comparative analysis of positional encoding strategies based on the Fiedler vector and eigenvector centrality.
- Evaluation of their impact on tasks such as node classification, segmentation, and regression on graphs and meshes.
- Insights into the effectiveness of spectral-based encodings in enhancing the performance of GNNs and Transformers on geometric data.

#### References (State of the Art)

- Kreuzer et al. (2021). Rethinking Graph Transformers with Spectral Attention. NeurIPS 2021. https://openreview.net/pdf?id=huAdB-Tj4yG
- Liu, R., et al. (2023). Graph Positional and Structural Encoder. arXiv. https://arxiv.org/pdf/2307.07107
- Ajayi, O., et al. (2024). NAPE: Numbering as a Position Encoding in Graphs. 
- Liang, B., et al. (2024). Centrality-guided Pre-training for Graph. OpenReview. https://openreview.net/forum?id=X8E65IxA73
- Huang, Y., et al. (2023). On the Stability of Expressive Positional Encodings for Graphs. arXiv. https://arxiv.org/abs/2310.02579