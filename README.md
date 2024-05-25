# Churn Prediction with Machine Learning
## Overview
This project focuses on predicting customer churn using machine learning techniques. We analyze a dataset related to customer behavior and churn rates. The project consists of two main parts: exploratory data analysis (EDA) and model building.

## Exploratory Data Analysis (EDA)
In the EDA phase, we use the plotly package to create insightful visualizations. Key steps include:

Understanding the dataset structure.
Identifying missing values.
Visualizing feature distributions.
Investigating correlations between features.
Exploring patterns related to churn.
## Model Building
#### AutoML with PyCaret:
Initially, we leverage the pycaret package for automated machine learning (AutoML). This helps us quickly evaluate multiple algorithms and identify promising models.
#### Data Preprocessing:
Based on insights from EDA, we perform data preprocessing:
Handling outliers.
Scaling features.
Addressing class imbalance.
#### Model Selection and Tuning:
We experiment with different classifiers, including:
Decision Tree.
Random Forest Classifier.
Hyperparameter tuning is done using GridSearchCV.
#### Interpreting Model Results:
Finally, we use shap to understand the most influential parameters in our chosen models.
