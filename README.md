# Bitcoin ML Analysis

## Overview
This project explores the use of machine learning models to analyze Bitcoin market data.

The analysis includes:
- Unsupervised learning (clustering)
- Regression modeling (predicting volatility)
- Classification (predicting return direction)

## Methods
- K-Means Clustering
- Linear Regression / Ridge Regression
- Random Forest (non-linear model)
- Logistic Regression (classification)

## Features
- Returns
- Volatility
- Volume changes
- Lagged variables (t-1)
- Technical indicators (EMA, RSI)

## Key Results
- Clustering identifies different market regimes (calm, bullish, volatile)
- Volatility prediction is driven strongly by lagged volatility
- Classification achieves ~53% accuracy using lagged features
- Technical indicators (EMA, RSI) do not improve predictive performance

## Key Insight
Financial markets are **noisy and difficult to predict**.  
While small predictive signals exist, they are weak and not easily exploitable.

## How to Run
1. Open the notebook (`bitcoin-ml-analysis.ipynb`)
2. Run all cells from top to bottom
3. Alternatively, view the HTML file for results

## Tech Stack
- Python
- pandas
- scikit-learn
- matplotlib

## Author
Viktor Már Eyjólfsson Ortega
