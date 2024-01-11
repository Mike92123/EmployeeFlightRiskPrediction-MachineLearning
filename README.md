# Employee Flight Risk Prediction Using Machine Learning Techniques
## Introduction
In today’s competitive job market, employee flight risk, the likelihood of employees voluntarily leaving a company, poses significant challenges. This project aims to analyze and predict employee attrition using a dataset of Fraser Health employees and contribute to effective employee retention strategies.

## Problem Statement
The project's goals are to:
Analyze objective factors impacting employee attrition.
Identify core causes prompting employees to leave.
Develop a predictive model assessing the likelihood of an employee's departure.

## Literature Review
Various machine learning techniques are explored in existing literature for predicting employee attrition, including Gaussian Naive Bayes, Logistic Regression, K-NN, Decision Tree, Random Forest, SVM, LSVM, and deep learning models.

## Methodology
Data Cleaning
The dataset underwent a thorough cleaning process, including:
Column removal for missing values.
Handling missing values in numerical and categorical columns.
Outlier detection and removal.
Data transformation for numerical analysis.
Categorical feature encoding using One-Hot and Frequency encoding methods.
## Models
Several models are explored:
Logistic Regression
K-Nearest Neighbors (K-NN)
Decision Tree Classifier
Random Forest
Neural Network
Specialized algorithms for imbalanced datasets like Isolation Forest, One-Class SVM, and Gradient Boost Machine are also incorporated.
## Experimental Results and Discussion
Preliminary Results
An analysis of the Fraser Health Authority's workforce turnover patterns provided insights into factors influencing employee decisions to leave.

Feature Selections
Key features identified include 'Ave_Age', 'HoursPerPeriod', 'Tenure', 'Compensation', 'Compensation_Change', and 'Hours_A'.

Models Evaluations and Comparisons
Accuracy of different models was compared, with Random Forest emerging as the most accurate.

Methods to Balance Imbalanced Dataset
Resampling techniques like undersampling and oversampling were employed to address dataset imbalances.

Additional Metrics
Beyond accuracy, metrics like True Negative Rate (TNR) and Negative Predictive Value (NPV) were used for a more nuanced understanding of the models.

## Conclusion and Future Work
The project provides insights into factors affecting employee turnover and the efficacy of various predictive models. 
Future work should explore the interactions between identified features and integrate external economic or industry-specific factors.

## References
Fallucchi F. et al. (2020): Predicting employee attrition using machine learning techniques.
PM U. and Balaji N.V. (2019): Analysing Employee attrition using machine learning.
Ponnuru S.A. et al. (2020): Employee attrition prediction using logistic regression.
Mhatre A. et al. (2020): Predicting employee attrition and identifying high-risk employees.
Arqawi S.M. et al. (2022): Predicting Employee Attrition and Performance Using Deep Learning.
Singh A. (2018): Antecedents affecting the flight risk or turnover intention of professionals.
Bennett B.P. (2020): Predicting Early Employee Flight During Preselection.
Punnoose R. and Ajit P. (2016): Prediction of employee turnover in organizations.
This README offers an overview of the final report focusing on predicting employee flight risk using machine learning techniques. The project encompasses comprehensive data analysis, methodology, model evaluations, and discussions on employee turnover at Fraser Health.
