![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white)
![License](https://img.shields.io/badge/License-Apache-green)
![Stars](https://img.shields.io/github/stars/Vaishvi12/FraudSight?style=social)
![Issues](https://img.shields.io/github/issues/Vaishvi12/FraudSight)

# FraudSight
**AI + XAI for Financial Fraud Detection** — an end-to-end project combining machine learning and deep neural networks with interpretability methods (XAI) to detect and explain fraudulent financial transactions.

---

## 🔎 Summary
FraudSight is an explainable AI pipeline that detects financial fraud using ML and DNN models, and provides human-understandable explanations using SHAP, LIME, PDP, and SHAPASH.

---

## 📂 What’s in this repo 
This repo includes step-by-step Jupyter notebooks covering the entire workflow:

- `1_Project_EDA.ipynb` — Exploratory Data Analysis, missing values, and feature engineering.  
- `1_Project_ANN_Modeling.ipynb` — Baseline ANN/DNN architecture, training, evaluation.  
- `1_Project_XAI_FeatureImportance_PDP.ipynb` — Feature importance and PDP interpretability.  
- `2_Project_ML_Modeling.ipynb` — ML models such as Logistic Regression, Random Forest, XGBoost/LightGBM.  
- `2_Project_CNN_Modeling.ipynb` — CNN for transformed/tabular sequence representations (optional).  
- `2_Project_XAI_SHAP.ipynb` — SHAP explanations (global + local).  
- `3_Project_ML_Handle_Class_Imbalance.ipynb` — SMOTE, class weighting, focal loss implementations.  
- `3_Project_XAI_LIME.ipynb` — LIME explanations for individual predictions.  
- `4_Project_ML_Tuning.ipynb` — Hyperparameter tuning (GridSearch, RandomizedSearch, Bayesian).  
- `4_Project_XAI_SHAPASH.ipynb` — SHAPASH dashboard and interpretability reports.

---

## ⭐ Highlights / Features
- End-to-end fraud detection pipeline: EDA → preprocessing → modeling → tuning → XAI.  
- Classical ML + Deep Learning hybrid modeling.  
- Advanced imbalance-handling strategies.  
- Model explainability with **SHAP**, **LIME**, **PDP**, and **SHAPASH**.  
- Fully reproducible and notebook-driven workflow.

---

## 🧠 Models & Techniques

### **Classical ML**
- Logistic Regression  
- Random Forest  
- XGBoost / LightGBM  

### **Deep Learning**
- Feedforward Deep Neural Networks (ANN)  
- Optional CNN architectures for feature transformation  

### **Imbalance Handling**
- SMOTE  
- Class weighting  
- Focal loss  

### **Hyperparameter Tuning**
- GridSearchCV  
- RandomizedSearchCV  
- Bayesian Optimization  

---

## 🔍 Explainable AI (XAI) Tools

- **SHAP** — global + local feature contributions based on Shapley values.  
- **LIME** — interpretable local linear approximations.  
- **PDP** — feature influence visualization.  
- **SHAPASH** — easy-to-read model reports and dashboards.  

---

## 📈 Evaluation Metrics

- **ROC-AUC**  
- **Precision**  
- **Recall**  
- **F1-score**  
- **PR-AUC** (recommended for high-class-imbalance domains)  
- Confusion matrices for error inspection  

---

## 📝 License
This project is licensed under the **Apache License**, which permits unrestricted use, modification, distribution, sublicensing, and commercial usage, provided that proper credit is given to the original authors.