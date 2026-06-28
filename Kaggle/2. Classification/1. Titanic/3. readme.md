# Module: Classification Pipelines

## 🎯 Objectives
This directory covers supervised learning for categorical outcomes, ranging from binary (Yes/No) to multi-class problems.

## ⚙️ Workflow & Testing
*   **Validation:** Using **Stratified Train-Test Splits** to keep the target class ratios consistent across datasets.
*   **K-Fold Cross-Validation:** Applying **Stratified K-Fold** to verify classifier stability across different data folds.
*   **Hyperparameter Tuning:** Utilizing **Randomized Search** to optimize model parameters without exhaustive grid sweeping.
*   **Multi-Model Testing:** Testing and benchmarking various classification algorithms (e.g., Random Forest [RF], XGBoost, Support Vector Classifier [SVC], and Logistic Regression).

## 📋 Implementation Checklist
- [x] Data Preprocessing & Categorical Encoding
- [x] Training and optimizing multiple classification models
- [x] Analyzing prediction breakdowns via Confusion Matrices
- [x] Performance tracking (Accuracy, Precision, Recall, and F1-Score)
