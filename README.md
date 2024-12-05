# Loan-Default-Prediction
Loan Default Prediction with Artificial Intelligence Machine Learning

## Project Overview

With the increasing demand for loans and the frequent default events in the bond market and credit market, the non-performing asset rate of commercial banks and the default risk of user personal loans have become core issues for the government and the banking industry. The effective assessment and measurement of credit loan default risk is a key task for commercial banks to improve their management.

This project focuses on personal credit in financial risk control. Based on the data of loan applicants, it predicts the possibility of default. The goal is to build various machine learning models to predict the likelihood of loan default using training data from historical loan default cases.

## Machine Learning Algorithms

In this experiment, some of the most popular algorithms in the field were used to train the loan default data. These include:
- Decision Tree
- Bagging
- RandomForest
- XGBoost
- LightGBM
- CatBoost

We utilized the five-fold cross-validation method for model training and used the AUC (Area Under the Curve) index as the evaluation metric to assess the performance of the models.

## Best Model and Results

After evaluating the six models, the CatBoost model achieved the best performance with an AUC score of 74.88%. This model was chosen as the best model for predicting loan defaults.

The project also includes a data visualization analysis report for better understanding of the results.
