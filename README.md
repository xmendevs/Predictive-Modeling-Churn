# Predictive-Modeling-Churn
Customer Churn Prediction for Zeolin Limited
This project focuses on building a robust machine learning model to predict customer churn for Zeolin Limited, a global telecommunications company. By analyzing customer behavior and service usage data, the model provides an early warning system to identify at-risk customers, enabling proactive retention strategies.

## Methodology & Techniques
Exploratory Data Analysis (EDA): Identified key patterns and class imbalance.

## Data Preprocessing: Handled categorical variables using one-hot encoding and scaled numerical features.

## Class Imbalance: Utilized SMOTE (Synthetic Minority Over-sampling Technique) to balance the training data, ensuring the model could effectively learn to predict the minority class (churn).

## Model Building: Developed and evaluated multiple classifiers, including Logistic Regression, Decision Tree, and Random Forest.

## Hyperparameter Tuning: Optimized the final Random Forest Classifier using Grid Search to achieve peak performance.

## Key Results
The final model achieved a high accuracy and a strong f1-score for the minority class, demonstrating its ability to reliably predict churn. The project's feature importance analysis identified key drivers of churn, such as the number of customer service calls and international plan usage, providing actionable business insights.
