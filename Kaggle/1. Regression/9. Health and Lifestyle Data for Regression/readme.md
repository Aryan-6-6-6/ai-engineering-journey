# 🩺 Health Score Prediction Using Machine Learning

## 📖 Overview

This project predicts an individual's **Health Score** using **Linear Regression**. It follows a complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, preprocessing, hyperparameter tuning using **GridSearchCV**, cross-validation, and model evaluation.

**📓 Kaggle Notebook:** https://www.kaggle.com/code/abacilla/health-and-lifestyle-data-for-regression

---

# 📊 Dataset

The project uses the **Health and Lifestyle Dataset**, which contains demographic, lifestyle, and health-related attributes such as **Age, BMI, Sleep Hours, Exercise Frequency, Diet Quality, Stress Level**, and more to predict an individual's **Health Score**.

**📂 Dataset:** https://www.kaggle.com/datasets/pratikyuvrajchougule/health-and-lifestyle-data-for-regression

---

# ⚙️ Project Workflow

* 📥 Data Loading & Understanding
* 🧹 Data Cleaning
* 📈 Exploratory Data Analysis (EDA)

  * Univariate Analysis
  * Multivariate Analysis
* 🔧 Feature Engineering & Preprocessing
* 📏 Feature Scaling
* 🎯 Hyperparameter Tuning using GridSearchCV
* 🤖 Model Training
* 📊 Model Evaluation

---

# 🤖 Model Used

* Linear Regression

---

# 🏆 Results

The **Linear Regression** model was optimized using **GridSearchCV** and validated using **5-Fold Cross Validation** before being evaluated on the test dataset.

### 📈 Cross Validation Performance

| Metric                         |      Value |
| ------------------------------ | ---------: |
| Best Cross-Validation R² Score | **0.8331** |

### 📈 Test Performance

| Metric                   |       Value |
| ------------------------ | ----------: |
| R² Score                 |  **0.8090** |
| Mean Squared Error (MSE) | **37.2409** |

### 🔍 Key Findings

* ✅ **GridSearchCV** identified the optimal Linear Regression parameters.
* ✅ The model achieved a **Cross-Validation R² Score of 0.8331**, demonstrating consistent performance across data splits.
* ✅ The final model obtained a **Test R² Score of 0.8090**, indicating strong predictive capability for estimating health scores.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

# 🚀 Future Improvements

* Compare the optimized Linear Regression model with regularized regression techniques such as **Ridge**, **Lasso**, and **ElasticNet**.
* Evaluate the model using different **K-Fold values** (e.g., 10-Fold or Repeated K-Fold Cross Validation) to analyze the stability of model performance.
* Investigate feature importance and multicollinearity to better understand which lifestyle factors contribute most to health score prediction.
* Collect a larger and more diverse dataset to improve the model's generalization on unseen data.

---

# 📚 Learning Outcomes

Through this project, I learned:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering and feature scaling
* Hyperparameter tuning using GridSearchCV
* K-Fold Cross Validation
* Building and optimizing a Linear Regression model
* Model evaluation using **R² Score** and **Mean Squared Error (MSE)**

---

# 👨‍💻 Author

**Aryan Gupta**

Part of the **AI Engineering Journey** repository.
