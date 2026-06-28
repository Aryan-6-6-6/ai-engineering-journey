# Employee Salary Prediction Using Machine Learning

## Overview

This project predicts employee salaries using multiple Machine Learning regression models. It demonstrates a complete ML workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model comparison to identify the best-performing regression algorithm.

**🔗 Kaggle Notebook:** https://www.kaggle.com/code/abacilla/employee-data

---

## Dataset

The dataset contains employee-related information such as demographic, educational, and professional attributes, with **Salary** as the target variable.

---

## Project Workflow

* Data Loading and Inspection
* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Feature Engineering
* Encoding and Feature Scaling
* Model Training
* Model Evaluation and Comparison

---

## Models Used

* Linear Regression
* Ridge Regression
* Lasso Regression
* ElasticNet Regression

---

## Results

The models were evaluated using **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, and **R² Score**.

| Model             |         MSE |      RMSE |   R² Score |
| ----------------- | ----------: | --------: | ---------: |
| Linear Regression |  17,375,020 |  4,168.34 | **0.9918** |
| Ridge Regression  |  17,402,270 |  4,171.60 |     0.9917 |
| Lasso Regression  |  17,530,350 |  4,186.93 |     0.9917 |
| ElasticNet        | 292,894,000 | 17,114.15 |     0.8610 |

🏆 **Best Model:** **Linear Regression**, achieving an **R² Score of 0.9918**, indicating excellent predictive performance on the employee salary dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Future Improvements

* Perform hyperparameter tuning for better model performance.
* Train advanced ensemble models such as Random Forest, XGBoost, and Gradient Boosting.
* Deploy the model using Streamlit or Flask.
* Explore additional feature engineering techniques to further improve prediction accuracy.

---

## Learning Outcomes

Through this project, I learned:

* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Feature encoding and scaling
* Building and comparing multiple regression models
* Model evaluation using MSE, RMSE, and R² Score
* Selecting the best-performing model based on evaluation metrics

---

## Author

**Aryan Gupta**

Part of my **Machine Learning & Data Science Portfolio**.
