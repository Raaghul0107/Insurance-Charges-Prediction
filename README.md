# Insurance-Charges-Prediction

## Project Overview

This project involves the development of a machine learning model to predict insurance charges incurred by the users based on various features. The primary goal is to explore different regression techniques and evaluate their performance in predicting insurance charges.

## Dataset

The dataset used in this project includes several attributes potentially influencing insurance costs, such as age, BMI, number of children, smoking status, and region. 

Data Source : https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance  (1337 records, 7 columns)

## Requirements

List of libraries

numpy
pandas
scikit-learn
matplotlib
seaborn

## Methodology

Linear Regression
Random Forest Regression

## Key steps involved:
Exploring the data: Explored each variables distribution with distplot and countplot.

Data Preprocessing: Handling missing values, encoding categorical variables.

Model Training: Using different regression models to train on the dataset.

Model Evaluation: Evaluating models using metrics like Mean Squared Error (MSE) and R-squared (R²).

Hyperparameter Tuning: Improving RF model performance through hyperparameter optimization.

Comparison: Concluded the project with a comparative analysis of the predicted insurance charges from both models against the actual charges incurred, providing a critical assessment of model accuracy and reliability in real-world scenarios.

## Results
The models were evaluated based on their MSE and R² scores. After hyperparameter tuning, the Random Forest model showed a significant improvement in generalizing to unseen data. Random forest model is comparitively better than Linear Regression model in predicitng the charges.

