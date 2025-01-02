# Heart Disease Prediction with Linear Regression

This repository contains a Jupyter Notebook that implements a linear regression model to predict the presence of heart disease based on patient health data.

## Overview

The notebook performs the following steps:

1.  **Data Loading and Exploration:**
    *   Loads the dataset from a CSV file (`heart_disease_data.csv`).
    *   Displays the first few rows and descriptive statistics.
    *   Checks for missing values and duplicate rows, handling any found.
2.  **Data Preprocessing:**
    *   Scales numerical features (`age`, `trestbps`, `chol`, `thalach`, `oldpeak`) using `StandardScaler`.
3.  **Model Training:**
    *   Splits the data into training and testing sets (80/20 split).
    *   Trains a linear regression model using `sklearn.linear_model.LinearRegression`.
4.  **Model Evaluation:**
    *   Predicts heart disease using the test set.
    *   Calculates the accuracy score using the model's predictions, using a threshold for binary classification
    *   Visualizes the comparison between actual and predicted values using a scatter plot.

## Dataset

The dataset used for this project is `heart_disease_data.csv`, which contains the following features:

*   `age`: Age of the patient.
*   `sex`: Gender (1 = male, 0 = female).
*   `cp`: Chest pain type.
*   `trestbps`: Resting blood pressure.
*   `chol`: Serum cholesterol.
*   `fbs`: Fasting blood sugar (1 if > 120 mg/dl, 0 otherwise).
*   `restecg`: Resting electrocardiographic results.
*   `thalach`: Maximum heart rate achieved.
*   `exang`: Exercise induced angina (1 = yes
