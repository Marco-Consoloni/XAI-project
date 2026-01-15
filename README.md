# Explainable AI (XAI) – Plant Disease Classification

This repository contains the Explainable Artificial Intelligence (XAI) project, carried out as part of a 30-hour course in XAI (2023-2024) organized by:

- Department of Informatics, University of Pisa; 
- National PhD Course in Artificial Intelligence.

The course focuses on:
- Motivations behind XAI;
- Core XAI methods and libraries;
- Open research challenges in XAI.

## Project Overview
Plant disease classification from images presents several key challenges:

- Early detection during initial phases of infection;
- Detection in non-homogenous and complex backgrounds;
- Detection on both single and multiple overlapping leaves.

To address these challenges, we trained two deep learning models for plant disease classification and analyzed their detection capabilities using post-hoc XAI techniques, including: **IntGrad**, **Rise**, **LIME** and **Grad-CAM++** .

![readme_img](assets/readme_img.png)

**Figure 1.** Example of saliency maps of strawberry leaves affected by the leaf scorch disease with non-homogeneous background.

These methods enable the interpretation of model predictions by highlighting the most relevant image regions contributing to each classification decision (see Figure 1).

- **Code:** [`XAI_project_code.ipynb`](./XAI_project_code.ipynb)
- **Report:** [`XAI_project_report.pdf`](./XAI_project_report.pdf)






