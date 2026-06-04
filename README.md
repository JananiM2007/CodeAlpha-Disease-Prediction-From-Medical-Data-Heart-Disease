# CodeAlpha-Disease-Prediction-From-Medical-Data-Heart-Disease
Heart Disease Prediction using Logistic Regression with feature selection and data preprocessing.
# ❤️ Heart Disease Prediction using Logistic Regression

## Project Overview

Heart Disease Prediction is a Machine Learning project that predicts whether a patient is likely to have heart disease based on various clinical and health-related attributes. The model was developed using Logistic Regression and achieved an accuracy of **88%** with a **ROC-AUC score of 93.5%**.

## Dataset

- Source: Kaggle
- Contains patient health records and clinical measurements.
- Target Variable: `HeartDisease`
  - 0 = No Heart Disease
  - 1 = Heart Disease

## Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

## Project Workflow

### Data Preprocessing
- Data cleaning and exploration
- One-Hot Encoding of categorical features
- Feature Scaling using StandardScaler

### Feature Selection

#### Pearson Correlation Analysis
Used to analyze the relationship between numerical features and the target variable.

#### Chi-Square Test
Used to identify the most significant categorical features associated with heart disease.

### Model Training
- Train-Test Split
- Logistic Regression Model

### Model Evaluation
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

## Results

| Metric | Score |
|----------|----------|
| Accuracy | 88% |
| Precision | 89% |
| Recall | 89% |
| F1-Score | 89% |
| ROC-AUC Score | 93.5% |

### Classification Report

| Class | Precision | Recall | F1-Score |
|---------|-----------|--------|----------|
| No Heart Disease (0) | 0.87 | 0.87 | 0.87 |
| Heart Disease (1) | 0.89 | 0.89 | 0.89 |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Future Improvements

- Hyperparameter tuning
- Compare multiple machine learning algorithms
- Deploy as a web application
- Use larger healthcare datasets

## Author

**Janani M**
