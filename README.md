:

📘 Student Score Prediction

📌 Predicting Student Exam Scores

This project focuses on predicting students' exam scores based on several factors such as study hours, attendance, parental involvement, access to resources, and more.

The dataset used: Student Performance Factors (Kaggle)

📝 Description

Load and preprocess the dataset

Perform Exploratory Data Analysis (EDA) and visualizations

Handle missing values and outliers

Feature engineering (e.g., log-transforming tutoring sessions)

Train multiple regression models:

Linear Regression

Ridge Regression

Lasso Regression

Evaluate models using R² and RMSE

Compare performance across models

🛠 Tools & Libraries

Python

Pandas – Data handling

NumPy – Numerical operations

Matplotlib / Seaborn – Data visualization

Scikit-learn – Modeling, preprocessing, evaluation

📊 Covered Topics

Data Cleaning & Preprocessing

Handling Missing Values & Outliers

Exploratory Data Analysis (EDA)

Feature Engineering

Regression Models (Linear, Ridge, Lasso)

Evaluation Metrics (RMSE, R²)

⚡ Workflow

Load Dataset
Load StudentPerformanceFactors.csv from Kaggle.

Data Cleaning & Preprocessing

Removed missing values

Fixed exam scores > 100

Applied log transformation on tutoring sessions

EDA (Exploratory Data Analysis)

Visualized distributions of features (Hours_Studied, Attendance, etc.)

Analyzed categorical columns (Parental_Involvement, Access_to_Resources, etc.)

Detected and visualized outliers

Feature Engineering & Selection

Numeric + categorical features separated

Applied One-Hot Encoding to categorical features

Standardized numeric features

Modeling

Linear Regression

Ridge Regression (α=0.5)

Lasso Regression (α=0.1)

Evaluation
Metrics used:

Root Mean Squared Error (RMSE)

Coefficient of Determination (R²)

📈 Results
Model	Train R²	Test R²	Test RMSE
Linear Regression	0.673	0.701	2.156
Ridge Regression	–	0.701	2.156
Lasso Regression	–	0.668	2.273

👉 Ridge and Linear Regression performed similarly, while Lasso underperformed slightly.

🚀 How to Run

Clone the repository

Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook / Colab file

📌 Future Work

Add Polynomial Regression for non-linear patterns

Try ElasticNet Regression (combination of Ridge + Lasso)

Hyperparameter tuning with GridSearchCV

Compare with advanced models (Random Forest, XGBoost)
