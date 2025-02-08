# Bank Client Churn Prediction
## Project Overview
This project aims to predict whether a bank client will exit or remain using a variety of machine learning models. The dataset used contains information about bank clients, such as their credit score, demographics, and usage patterns. The models employed to predict customer churn are:

Multilayer Perceptron (MLP)
Support Vector Machine (SVM)
Logistic Regression
K-Nearest Neighbors (KNN)
Dataset

## The dataset consists of the following features:

CreditScore: The client's credit score
Geography: The region of the client
Gender: The gender of the client
Age: The client's age
Tenure: The number of years the client has been with the bank
Balance: The account balance of the client
NumOfProducts: The number of products the client has with the bank
HasCrCard: Whether the client has a credit card (1: Yes, 0: No)
IsActiveMember: Whether the client is an active member (1: Yes, 0: No)
EstimatedSalary: The client's estimated salary
Exited: The target variable indicating whether the client has exited (1: Exited, 0: Stayed)
Goal
The goal of this project is to predict whether a client will exit (churn) or remain with the bank based on their features. The project utilizes various classification models to compare performance and select the most accurate model.

## Models Used
1. Multilayer Perceptron (MLP)
A neural network model used for classification tasks. This model learns complex patterns in data and can perform well for non-linear decision boundaries.

2. Support Vector Machine (SVM)
A model that finds the optimal hyperplane to classify data points. It's useful for high-dimensional spaces and is effective when there is a clear margin of separation.

3. Logistic Regression
A classical statistical model used for binary classification. It estimates the probability of a client exiting based on their features.

4. K-Nearest Neighbors (KNN)
A non-parametric method that classifies a client based on the majority vote of its nearest neighbors in the feature space.


## Evaluation Metrics
The following metrics are used to evaluate the models:

Accuracy: The proportion of correctly classified instances
Precision: The proportion of positive instances correctly predicted
Recall: The proportion of actual positive instances identified
F1 Score: The harmonic mean of precision and recall
Results
After training and testing the models, the results will be displayed in a classification report. The model with the highest performance will be selected for further use.

## Conclusion
This project demonstrates how various machine learning models can be applied to predict client churn in the banking sector. By understanding customer behavior and predicting churn, banks can improve retention strategies and minimize losses.
