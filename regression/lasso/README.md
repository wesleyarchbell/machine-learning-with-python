# Lasso Regression - House Price Prediction

## Overview
This example demonstrates Lasso Regression for predicting house prices using multiple features. Lasso Regression is particularly useful in this scenario because:

1. It performs feature selection by eliminating less important features
2. It helps prevent overfitting when dealing with many features
3. It produces sparse models that are easier to interpret

## Dataset Features
- Square feet
- Number of bedrooms
- Number of bathrooms
- House age
- Garden size
- Distance to city

## Why Lasso Regression?
Lasso Regression is ideal for this housing dataset because:
- It automatically identifies the most important features affecting house prices
- It reduces the impact of less relevant features
- It handles multicollinearity between features (e.g., correlation between square feet and number of bedrooms)

## Results
As shown in the notebook:
- R² score of 0.873 on test data
- Average prediction error of 6.67%
- Most important features (in order):
  1. Square feet
  2. Number of bedrooms
  3. Number of bathrooms
  4. Garden size

## Code Reference
The implementation can be found in `lasso_regression.ipynb`