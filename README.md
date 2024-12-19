# Customer Churn Prediction Using Machine Learning Models
Overview

This repository contains the final project for ALY6020 - Predictive Analytics. 

The objective of this project is to predict customer churn by leveraging demographic and behavioral data. 

Through comprehensive analysis and the implementation of various machine learning models, we explore factors influencing customer attrition and recommend the most suitable predictive model.

Project Description

Dataset Size: 10,000 records with 14 features.

Target Variable: Exited (indicates whether a customer churned).

Features: Includes demographic details like age, nationality, and gender, as well as banking activity metrics like credit card ownership and number of products used.

Goals

Identify key factors influencing customer churn.

Build predictive models using various machine learning techniques.

Evaluate and compare model performance using metrics like accuracy, precision, recall, and runtime.

Recommend the most effective model for customer churn prediction.

Project Phases:

Data Cleaning

Removed irrelevant columns, handled missing values, and addressed outliers using the Interquartile Range (IQR) method.

Exploratory Data Analysis (EDA)

Uncovered key trends such as churn rate by age and activity level, and identified correlations between features.

Model Development

Implemented the following machine learning models:

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Gradient Boosting

Support Vector Machine (SVM) with Linear, RBF, and Polynomial Kernels

Neural Network Each model was optimized using hyperparameter tuning

Performance Evaluation

Models were assessed using training and testing datasets. Metrics include:

Accuracy

Precision and recall for both churned and non-churned classes

Runtime efficiency

Model Comparison

Gradient Boosting emerged as the best-performing model with an accuracy of 85.20%, followed by Random Forest (84.25%).

Key Findings

Older customers and those from specific regions (e.g., Germany) are more likely to churn.

Active members are significantly less likely to churn.

Gradient Boosting achieved the best balance of accuracy, precision, and recall, making it the most effective model for this task.


