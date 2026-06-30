# AI-Based Diabetes Prediction System

## Overview

The AI-Based Diabetes Prediction System is a Machine Learning project that predicts whether a person is diabetic based on various health-related parameters. The project uses a Random Forest Classifier to analyze patient data and classify individuals as diabetic or non-diabetic.

This project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, visualization, and prediction.


## Features

- Data preprocessing and cleaning
- Handling categorical variables using One-Hot Encoding
- Feature scaling using StandardScaler
- Random Forest Classification model
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
  - ROC-AUC Curve
- Data visualization
- Predict diabetes using custom patient data


## Dataset

**Dataset Used:** Diabetes Prediction Dataset

The dataset contains information such as:

- Gender
- Age
- Hypertension
- Heart Disease
- Smoking History
- BMI
- HbA1c Level
- Blood Glucose Level
- Diabetes (Target Variable)

Target Variable:
- **0 → Non-Diabetic**
- **1 → Diabetic**


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


## Machine Learning Workflow

### 1. Data Preprocessing
- Loaded dataset
- Checked missing values
- One-Hot Encoding
- Feature Scaling using StandardScaler

### 2. Model Training
- Random Forest Classifier

### 3. Model Evaluation
- Confusion Matrix
- Classification Report
- ROC Curve
- ROC-AUC Score

### 4. Prediction System
The model predicts whether a patient is:
- Diabetic
- Non-Diabetic

along with the prediction confidence.


## Results

- Model Accuracy: **97%**
- ROC-AUC Score: **0.97**
- High Precision and Recall
- Excellent classification performance
