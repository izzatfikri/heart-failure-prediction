# Heart Failure Prediction Model

## Project Overview

This project aims to develop a machine learning classification model to predict the likelihood of heart disease in individuals based on clinical data. Cardiovascular diseases (CVDs) are the leading cause of death globally, making early detection crucial for improving patient outcomes. By leveraging machine learning techniques, this project seeks to identify high-risk patients, enabling timely and effective intervention strategies.

## Dataset

The dataset used for this project is the **Heart Disease Prediction dataset** retrieved from https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/. It contains various clinical features that contribute to heart disease risk assessment.

## Algorithms Used

Four machine learning algorithms were evaluated for their performance in predicting heart disease:

- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

### Results

- **Best Performing Model**: 
  - **Random Forest**: Achieved **88% accuracy** and a **0.94 AUC (Area Under the Curve)** score, demonstrating effective prediction capabilities.
  
- **Other Model Performances**:
  - **Logistic Regression**: 87% accuracy, 0.93 AUC
  - **K-Nearest Neighbors (KNN)**: 86% accuracy, 0.93 AUC
  - **Decision Tree**: 77% accuracy (improved to 83% after hyperparameter tuning)
