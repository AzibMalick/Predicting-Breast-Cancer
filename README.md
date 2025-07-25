# Breast Cancer Classification using SVM & Naive Bayes

This machine learning project uses the **Wisconsin Breast Cancer Diagnostic Dataset** to predict whether a tumor is **malignant** or **benign** based on real-world clinical features.

It compares the performance of **Support Vector Machine (SVM)** and **Naive Bayes** models to assist in **early cancer diagnosis**.

---

## Dataset Overview

- **Source**: UCI Machine Learning Repository / [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Samples**: 569
- **Features**: 30 numeric features (e.g., mean radius, texture, smoothness, symmetry)
- **Target**: 
  - `0` → Malignant
  - `1` → Benign

---

## Project Features

- Data Loading & Exploration  
- Feature Scaling with `StandardScaler`  
- Model Training using:
  - **Support Vector Machine (SVM)**
  - **Naive Bayes (GaussianNB)**
- Accuracy Score & Confusion Matrix  
- Comparative Analysis & Healthcare Interpretation  
- Markdown conclusions to communicate clinical insights  

---

## Results

| Model         | Accuracy |
|---------------|----------|
| SVM           | 95.61%   |
| Naive Bayes   | 96.49%   |

 **Naive Bayes outperformed SVM**, making it a strong contender for use in real-world triage tools due to its simplicity and speed.

---

## Key Takeaways

- ML models can assist in **early detection of cancer**.
- Even with a small dataset, **well-chosen models** give high accuracy.
- Probabilistic models like Naive Bayes may outperform complex ones in clean, structured healthcare datasets.

---

## Files Included

- `breast-cancer-classification.ipynb` – Source code notebook  
- `requirements.txt` – Python libraries used  
- 'Breast-Cancer.csv' - Dataset acquired from Kaggle
---
 Author
Developed by Azib Malick
© 2025 Azib Malick. All rights reserved.
