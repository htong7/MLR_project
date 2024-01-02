# Predictive Analytics for Medical Insurance Cost

## Overview

This project involved building a regression model to predict medical insurance charges using attributes like age, BMI, number of children, smoking status, and region. The data was obtained from a Kaggle dataset containing 1,337 observations.

The final chosen model was:

```
charges ~ age + bmi + children + smoker
```

with robust standard errors to account for heteroscedasticity.

## Key Findings

- Smokers had significantly higher medical charges compared to non-smokers
- There were some differences in BMI across regions
- The final model had an adjusted R-squared of 0.7996, indicating a decent fit

## Challenges 

- Violations of linear regression assumptions like non-normality and non-linearity persisted despite data transformations
- Potential autocorrelation was detected but not definitively confirmed

## Contents

The report includes details on:

- Data preprocessing 
- Exploratory data analysis
- Regression analysis and model selection
- Final model diagnosis
- Summary of results

## Authors
Ho Nam (Felix) Tong, Eren Bardak, Mark Lam
