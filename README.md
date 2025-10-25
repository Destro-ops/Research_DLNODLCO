# 🫁 DLNO–DLCO Post-COVID Lung Function Prediction

This repository contains code and models developed for a research project analyzing and predicting post-COVID lung diffusion parameters — **DLNO** (Diffusing Capacity of the Lung for Nitric Oxide) and **DLCO** (Diffusing Capacity of the Lung for Carbon Monoxide).  

The study focuses on understanding gas transfer impairments in post-COVID patients using machine learning and statistical modeling approaches.

---

## 📘 Project Overview

After COVID-19, many patients experience long-term pulmonary diffusion abnormalities.  
This project aims to:
- Predict **DLNO** and **DLCO** values (or z-scores) based on spirometry, demographic, and clinical parameters.
- Identify the most influential features affecting gas transfer.
- Compare multiple ML algorithms for predictive performance.

---

## 🧠 Methodology

### 1. Data Preprocessing
- Handling missing values and outliers.
- Normalization / standardization of numerical features.
- Encoding of categorical variables.
- Feature selection based on correlation and variance thresholds.

### 2. Model Development
Implemented and compared multiple machine learning models:
- **Linear Regression / Ridge /**
- **Random Forest Regressor**
- **CatBoost Regressor**
- **Gradient Boosting Regressor**
- **LightGBM**
- **XGboost**
- **SVR**

Poorly performing models were tuned using **GridSearchCV / Optuna / bayesian** for optimal hyperparameters.

### 3. Core Evaluation Metrics
- **RMSE (Root Mean Square Error)**
- **MAE (Mean Absolute Error)**
- **R² Score**
- **Pearson / Spearman Correlation**
- **Concordance Correlation Coefficient (CCC)**

---

## 🧾 Results Summary
| Model | RMSE | MAE | R² | CCC |
|:------|:----:|:---:|:--:|:---:|
| CatBoost | — | — | — | — |
| Random Forest | — | — | — | — |
| Linear Regression | — | — | — | — |



