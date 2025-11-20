---
title: Reconstruction and Classification of 3D Brain Shapes Using Data-Driven and Handcrafted Features
contact_name: Simone Melzi 
contact_email: simone.melzi@unimib.it
date: 2025-11-20 00:00:00-0000
assigned: false
# image: 3DiG.png # uncomment to show the image from assets/img/
# tags:
#     - bachelor's
#     - master's
#     - computer vision
#     - geometric deep learning

---

This thesis aims to generate and study a collection of 3D shapes derived from
real medical volumetric acquisitions and their corresponding segmentation.
Specifically, the project will focus on brain magnetic resonance imaging (MRI)
data to reconstruct surface representations of relevant brain structures. From
these 3D reconstructions, geometric features will be extracted using both
data-driven (e.g., deep learning-based feature embeddings) and non-data-driven
(e.g., handcrafted geometric descriptors such as curvature) approaches.
Ultimately, these features will be employed in a practical classification
scenario, such as distinguishing between healthy and pathological brain
structures using standard machine learning models (e.g., Support Vector
Machines).

#### Data

The dataset consists of real 3D MRI volumes representing both healthy and
pathological brains. Each volume includes segmentation labels for relevant
brain, which will be used to derive their surface mesh representations.

#### Expected Outcomes

- Extraction of 3D brain surfaces from clinical MRI data and creation of a curated collection of 3D shape models.

- Extraction of geometric features from the reconstructed shapes using both data-driven and non-data-driven approaches.

- Application of classification models to the extracted features to perform a binary classification task (i.e., distinguishing healthy from pathological cases).


#### References (State of the Art)

- Li et al., MedShapeNet: a large-scale dataset of 3D medical shapes for computer vision. Biomedizinische Technik (Biomedical Engineering)
