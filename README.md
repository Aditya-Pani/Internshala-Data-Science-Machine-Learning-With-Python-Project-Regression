# 🧠 TechWorks Consulting – Salary Prediction Using Machine Learning
## 📁 Project Overview
This project is part of the Data Science Post Graduate Course by Internshala Trainings. The goal is to build a machine learning regression model that accurately predicts the salary of newly hired employees at TechWorks Consulting, based on historical data and several employee-related features.

## 🧩 Problem Statement
TechWorks Consulting wants to determine fair and competitive salaries for new employees using a data-driven approach. Given historical data that includes:

College Tier (Tier1, Tier2, Tier3)

City Type (Metro or Non-Metro)

Role (Manager/Executive)

Previous CTC

Previous Job Change

Graduation Marks

Work Experience

Current CTC

...our task is to:

Build a regression model that predicts the employee's salary (CTC) based on these features.

## 🛠 Technologies Used
Python

Jupyter Notebook

pandas, numpy – Data manipulation

matplotlib, seaborn – Visualization

scikit-learn – Machine Learning

statsmodels – Statistical testing

## 🔍 Steps Covered in Notebook
### 📌 1. Exploratory Data Analysis (EDA)
Dataset loading and initial inspection

Understanding feature distributions

Checking for null values and data types

### 📌 2. Data Preprocessing
Converting:

College → Numerical (Tier1: 1, Tier2: 2, Tier3: 3)

City → Binary (Metro: 1, Non-Metro: 0)

Role → Dummy variables (Role_Manager, Role_Executive)

Handling:

Missing values

Outliers (using IQR or z-score method)

Feature scaling (if required)

### 📌 3. Model Selection & Training
Tested various regression models:

Linear Regression

Ridge Regression

Lasso Regression

Decision Tree Regressor

Random Forest Regressor

### 📌 4. Model Evaluation
Metrics used:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R²)

Best model selected based on performance metrics

### 📌 5. Conclusions & Future Steps
Answered the required markdown questions:

Project views

Modeling approach

Model comparison

Best performing model

Potential improvements

## 🏁 Final Output
Final trained model: [Model Name, e.g., RandomForestRegressor]

Best performance: [e.g., R² = 0.88, RMSE = 23,000]

Reasons for selection: Handles non-linear relationships and performs well without overfitting

Improvement areas:

Hyperparameter tuning using GridSearchCV

Feature engineering (e.g., interaction terms)

Including more external data (e.g., industry-level salary benchmarks)
