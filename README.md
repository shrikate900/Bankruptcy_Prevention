# Bankruptcy_Prevention

## Introduction
This is a machine learning project that predicts the bankruptcy of a company using various financial features. The project includes data preprocessing, model selection, and evaluation. The best-performing model has an accuracy of 99.60%.

## Objective

This is a classification project, since the variable to predict is binary (bankruptcy or non-bankruptcy).  The goal here is to model the probability that a business goes bankrupt from different features.
The data file contains 7 features about 250 companies.

## Prerequisites
The following packages are required to run the project:
- numpy
- pandas
- scikit-learn
- matplotlib

## Preprocessing
The data is preprocessed to handle missing values, outliers, and scaling issues. 

## Models
The following machine learning models are used to predict the bankruptcy of a company:
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Support Vector Machine
- Random Forest
- Gradient Boosting

## Results
The performance of each model is evaluated using accuracy, and the best-performing model is Logistic Regression, achieving an accuracy of 99.60%.

## Conclusion
This project provides a framework for predicting the bankruptcy of a company using machine learning algorithms. The best-performing model can be used as a reference for future projects with similar objectives.

## Challenges Faced 

As the data set contains only 3 unique values and half of the values are identified as duplicated values and more the size of the data is small with 250 entries which results in inaccurate reporting, data integrity problem.
The biggest challenge is identifying the result in business point of view and making a decision on selecting the best model for deployment part.
