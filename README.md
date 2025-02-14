# Diabetes Health Indicators - Machine Learning Project

📌 Overview

This project analyzes the Diabetes Health Indicators dataset from Kaggle, leveraging machine learning models to predict diabetes based on behavioral, demographic, and health-related factors. The dataset, derived from the Behavioral Risk Factor Surveillance System (BRFSS) 2015, contains 253,680 records with 21 key features. Our goal is to develop and compare various classification models to improve diabetes prediction accuracy.

📊 Dataset Information

Source: Kaggle - Diabetes Health Indicators Dataset

Target Variable: Diabetes_binary (0 = No diabetes, 1 = Prediabetes or diagnosed diabetes)

Features: Age, BMI, physical activity, diet, blood pressure, smoking, alcohol consumption, general health status, and more.

🚀 Project Objectives

✔ Data preprocessing (handling missing values, outliers, and normalization)
✔ Exploratory Data Analysis (EDA) to find key correlations
✔ Model training using various classification algorithms
✔ Performance evaluation using accuracy, precision, recall, F1-score, and ROC AUC
✔ Hyperparameter tuning for optimized predictions
✔ Comparison of model performance to determine the best classifier

🔄 Data Preprocessing

Handled missing values using imputation methods.

Removed outliers in BMI using statistical analysis.

Feature scaling applied for optimal model performance.

Categorized BMI into Underweight, Normal, and Overweight.

Explored feature importance using SHAP and correlation analysis.

🎯 Results & Key Findings

Extra Trees achieved the highest accuracy with an ROC AUC score of 0.9849.

XGBoost and CatBoost also performed strongly, making them reliable choices for diabetes prediction.

Feature importance analysis showed that BMI, age, general health status, and physical activity were significant predictors.
