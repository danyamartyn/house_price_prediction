# House Prices: Advanced Regression Techniques

This repository contains my submission for the House Prices: Advanced Regression Techniques competition on Kaggle. In this competition, I was given a dataset with 79 explanatory variables describing residential homes in Ames, Iowa, and my goal was to predict the final sale price of each home.

## Project Overview

In this project, I followed the following steps:

1. Data Analysis: I explored the dataset to understand the distribution and relationship between the variables, and to identify any outliers, missing values, or data quality issues.

2. Data Cleaning and Preprocessing: I addressed the issues identified in the previous step, including imputing missing values, transforming variables, and encoding categorical variables.

3. Feature Engineering: I created new features based on domain knowledge and insights from the data analysis, including combining or transforming existing variables, and creating interaction terms.

4. Dimensionality Reduction: I applied Principal Component Analysis (PCA) to reduce the dimensionality of the dataset while retaining most of the variance, to improve the performance of my models and reduce the risk of overfitting.

5. Model Selection and Tuning: I applied several machine learning models to the preprocessed and feature engineered dataset, including Linear Regression, Decision Forest, Gradient Boosting, and Neural Networks, and tuned their hyperparameters using cross-validation and grid search.

6. Model Evaluation and Interpretation: I evaluated the performance of my models on the test set using Root-Mean-Squared-Error (RMSE), and interpreted the results to identify the strengths and weaknesses of each model and any insights into the data.

## Requirements

To run the code in this repository, you will need the following libraries:

pandas
numpy
scipy
seaborn
matplotlib
sklearn
xgboost
keras

## Result

My best performing model was a Gradient Boosting Regressor with an RMSE score of 26171.
