# Polynomial Regression - House Price Analysis

## Overview
This example uses Polynomial Regression to model the relationship between house square footage and price, capturing non-linear patterns in the data.

## Use Case
The model is particularly useful when:
- The relationship between variables isn't strictly linear
- Simple linear regression underfits the data
- There are clear curvilinear patterns in the data

## Why Polynomial Regression?
Polynomial Regression is ideal for this housing dataset because:
1. House prices often have a non-linear relationship with square footage
2. It can capture diminishing returns (e.g., price per square foot may decrease for very large houses)
3. It provides better flexibility than simple linear regression
4. It maintains the interpretability of regression models

## Results
As demonstrated in the notebook:
- R² score of 0.984 showing excellent fit
- Smooth curve fitting the data points
- Clear visualization of the non-linear relationship
- Comparison of actual vs. predicted prices

## Code Reference
The implementation can be found in `polynomial_regression.ipynb`