# Speed Dating Match Prediction 

## Overview
A machine learning project predicting the probability of a match 
in Speed Dating events, based on a dataset of 8,378 meetings 
and 195 variables from Columbia University research.

## Models Used
- Random Forest (AUC = 0.80)
- XGBoost (AUC = 0.83) 
- LightGBM (AUC = 0.82)

## Key Findings
- Mutual attractiveness ratings are the strongest match predictors
- Temporal features (Lag, Rolling Averages) significantly improved accuracy
- Demographic variables (age gap, race) showed minimal predictive power

## Methods
- Feature Engineering (Lag variables, Rolling Averages, Domain-Specific features)
- Walk-Forward Cross Validation
- ROC Curve Analysis
- Outlier detection using IQR method

## Tools & Libraries
Python | Pandas | Scikit-learn | XGBoost | LightGBM | Matplotlib
