# Module: Regression Analysis

## 🎯 Objectives
This directory focuses on predicting continuous target variables. The goal is to build stable models that minimize error across unseen data.

## ⚙️ Workflow & Testing
*   **Validation:** Implementation of **Train-Test Splits** to evaluate baseline model performance.
*   **K-Fold Cross-Validation:** Utilizing **K-Fold CV** to ensure the results are consistent and not dependent on a lucky data split.
*   **Hyperparameter Tuning:** Applying **Randomized Search (RandomizedSearchCV)** to efficiently find the best parameters for the models.
*   **Multi-Model Testing:** Comparing performance across multiple models (e.g., Support Vector Regressor [SVR], Regularized Regression [Ridge/Lasso], Decision Trees, and Ensembles).

## 📋 Implementation Checklist
- [x] Exploratory Data Analysis (EDA) & Data Cleaning
- [x] Handling Missing Values & Feature Scaling
- [x] Comparing performance across multiple regression models
- [x] Evaluating error using standard metrics (MSE, MAE, and R²)
