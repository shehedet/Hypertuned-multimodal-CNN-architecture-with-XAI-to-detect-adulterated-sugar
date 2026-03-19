# Sugar Adulteration Detection using Ensemble Learning

## Overview
This was part of our thesis for CSE undergrad, focusing on detection of sugar adulteration using advanced **deep learning ensemble techniques**. It combines multiple CNN architectures and incorporates uncertainty estimation and interpretability methods, making it suitable for **research and thesis-level work**. The ensemble model detects and classifies the level of known adulterations (adulterants that were used during training). For unknown adulterants, the model we used Mahalanobis Distance to compare it to pure sugar.

---

## Features

- Multiple deep learning models:
  - ResNet50  
  - DenseNet121  
  - ConvNeXt-Tiny  

- Ensemble Learning (Soft Voting)

- Test Time Augmentation (TTA)

- Uncertainty Estimation:
  - Monte Carlo Dropout  

- Out-of-Distribution Detection:
  - Mahalanobis Distance  

- Model Explainability:
  - Grad-CAM Heatmaps  

- Performance Evaluation:
  - Accuracy, Precision, Recall, F1-score  
  - Confusion Matrix  
  - Visualization tools  

---

## Model Architecture

This project uses an **ensemble approach**, combining predictions from multiple pretrained CNN models. The final prediction is obtained using **soft voting**, which improves robustness and accuracy compared to individual models.

---

## Contribution & Acknowledgment

This project is part of our undergraduate thesis conducted in the **Computer Science and Engineering (CSE) Department at :contentReference[oaicite:0]{index=0}**.

### Thesis Group Members
- **Anika Alamgir**
- **Nashita Anjum**
- **A. K. M. Shahadat Hossain**
- **Debpriyo Hrishikesh Deb Nath**

### Supervision
- **Supervisor:** Dr. Chowdhury Mofizur Rahman 
- **Co-Supervisor:** Rafeed Rahman

### Note
This repository represents a collaborative academic effort. All members contributed to the design, implementation, and evaluation of the project under the guidance of our supervisor and co-supervisor.
