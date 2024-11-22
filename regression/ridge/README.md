# Ridge Regression - Bitcoin Price Prediction

## Overview
This example uses Ridge Regression to predict Bitcoin's next-day closing price using historical price data. We'll use 4 years of Bitcoin price history to demonstrate how Ridge Regression can help us understand which factors most influence price movements.

## Use Case
Ridge Regression is useful when:
- There are many features in the dataset
- We want to prevent overfitting
- We want to understand which features are most important

## What We're Predicting
- Target Variable: Next day's Bitcoin closing price
- Prediction Window: 1 day ahead
- Data Timeframe: Last 4 years of Bitcoin data

## Features We'll Use
1. Previous closing prices
2. Trading volume
3. Price changes (daily, weekly)
4. Moving averages (7-day, 21-day, 50-day)
5. Volume trends
6. Basic technical indicators