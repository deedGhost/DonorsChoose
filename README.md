# DonorsChoose Project Approval Prediction

## Overview

This project involves building machine learning models to predict whether a project proposal on the DonorsChoose platform will be approved for funding. The dataset used for this analysis was sourced from the Kaggle. The project explores various models, including Logistic Regression, Decision Tree, Random Forest, and XGBoost, to identify the key factors that influence project approval.

## Dataset

The dataset is sourced from the [Kaggle](https://www.kaggle.com/code/saketranjan/group142-donorschoosedataset/notebook). It contains features related to teachers, schools, projects, and project descriptions, which are used to predict whether a project will be approved.

## Modeling

The project explores several machine learning models:

- **Logistic Regression**: Used both with and without hyperparameter tuning.
- **Decision Tree**: A tree-based model that helps understand feature importance.
- **Random Forest**: An ensemble method that averages multiple decision trees to improve accuracy.
- **XGBoost**: A powerful gradient boosting algorithm used with hyperparameter tuning.

## Results

The models were evaluated using metrics like accuracy and AUC (Area Under the Curve). The best model was selected based on cross-validation performance and its ability to generalize to unseen data.

- **Best Model**: XGBoost with hyperparameter tuning achieved the highest AUC score.

## Observations

- **Logistic Regression**: Provided a strong baseline with decent accuracy, but struggled with complex patterns. TEST ACCURACY-85% 
- **Decision Tree**: Overfit on the training data but gave insights into feature importance. TEST ACCURACY-75% 
- **Random Forest**: Improved generalization over Decision Tree but required more computation. TEST ACCURACY-85% 
- **XGBoost**: Outperformed other models, particularly after hyperparameter tuning, showing strong predictive power. TEST ACCURACY-85% 

