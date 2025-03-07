# [DMR] ✨

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)](https://github.com/tu-usuario/tu-repositorio/releases)



## Instalación 🔧

Follow this steps to install the project:

```bash
git clone https://github.com/AlonsoSolera/DMR.git
cd DMR
npm install

## Problem Statement:

This project addresses the challenge of customer churn prediction and analysis. The goal is to develop a model that accurately predicts which customers are likely to churn and to understand the factors driving churn. This information can then be used to develop targeted retention strategies and minimize revenue loss.

## Technology/Model Used:

The project utilizes a machine learning approach with the Random Forest algorithm as the primary model. Random Forest is an ensemble learning method that combines multiple decision trees to improve prediction accuracy and robustness. Additionally, XGBoost and Logistic Regression models are explored for comparison.

## Code Functionality:

## Data Preprocessing:

Outlier Handling: Outliers are identified and handled using both Z-score and IQR-based methods to improve data quality.
SMOTE: The Synthetic Minority Over-sampling Technique (SMOTE) is employed to address class imbalance issues, ensuring adequate representation of churned customers in the training data.
Model Training and Evaluation:

Random Forest: A Random Forest model is trained on the preprocessed data to predict customer churn.
Model Explainability: SHAP (SHapley Additive exPlanations) values are calculated to understand the contribution of each feature to the model's predictions, providing insights into churn drivers.

## Visualization:

Churn rate vs. contract type is visualized to analyze the relationship between these variables.
A confusion matrix is used to evaluate the model's performance in terms of true positives, true negatives, false positives, and false negatives.
A single tree from the Random Forest is visualized to illustrate the decision-making process.
Feature importance is plotted to identify the most influential features in predicting churn.
ROC Curve and Precision-Recall Curve are generated to assess the model's ability to distinguish between churners and non-churners.
Model Performance Enhancement:

Hyperparameter Tuning: GridSearchCV is used to find the optimal hyperparameters for the Random Forest model, maximizing its performance.
Alternative Models: XGBoost and Logistic Regression models are trained and compared to the Random Forest using ROC curves.
Business Impact Analysis:

Customer Segmentation: K-Means clustering is applied to segment customers based on their characteristics, providing insights for targeted marketing and retention efforts.
Economic Impact of Churn: The estimated lost revenue due to churn is calculated based on an assumed average credit value of $5000 per customer, highlighting the financial implications of churn.
