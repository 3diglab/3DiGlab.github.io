---
title: 3D Shape Visualization and Feature Function Mapping Framework
contact_name: Simone Melzi
contact_email: simone.melzi@unimib.it
date: 2025-10-28 00:00:00-0000
assigned: false
# image: 3DiG.png # uncomment to show the image from assets/img/
tags:
    - bachelor's
#     - master's
#     - computer vision
    - geometric deep learning

---
This thesis proposes the development of a comprehensive Python package for the advanced visualization of 3D geometric shapes. The framework is designed to support diverse geometric representations, including triangle meshes and point clouds (with potential integration for implicit representations such as Signed Distance Functions). The core objective is to enable the association and plotting of scalar and vectorial feature functions directly onto the geometric elements (vertices, edges, and faces) of the shapes.

#### Key Features

The package will implement the following core capabilities:

- Default Shape Rendering: visualization of 3D shapes using a customizable default shader.
- Scalar Function Mapping (Heatmaps): support for single-valued functions (1-valued) represented as color heatmaps.
- Vector Function Mapping (RGB Encoding): support for 3-valued functions, directly mapping components to RGB color channels for intuitive visualization.
- High-Dimensional Function Mapping: support for N-valued functions, allowing dimensionality reduction techniques (e.g., PCA into 3 dimensions) before RGB color encoding.
- Value Normalization and Clipping: robust data normalization (to [0, 1]) with user-defined input ranges and default fallbacks to min-max scaling, including value clipping for out-of-range inputs.
- Export Functionality: saving of plots in both interactive formats (HTML) and high-quality static images.
- Extensible Backend Architecture: a unified API design to facilitate support for multiple underlying rendering backends.

#### Technologies

- Python: Core programming language.
- PyTorch: for integration with deep learning pipelines and efficient tensor handling.
- Plotly and Matplotlib: For interactive and static 2D/3D plotting and data visualization components.
- Polyscope: As a primary candidate or reference for the 3D rendering backend due to its focus on geometric data visualization.

#### Expected Outcomes

- A fully documented and tested open-source Python package for 3D shape and function visualization.
- A flexible API that decouples the data visualization logic from the underlying rendering engine.
- Demonstrations of the tool's capabilities through the visualization of complex feature functions (e.g. geometric properties, neural network activations) on standard 3D models.
