# Superconductors
Predicting Critical Temperature of Superconductors. (R)

This project aims to analyse the chemical properties of superconductors and develope a model to predict critical tempretarue of superconductors.

## Outline

1. Introduction

2. Exploratory Data Analysis
    * Background Information about Attributes
    * Summary of Attributes
    * Summary of Findings from Distributions
    * Correlation Analysis Between Predictors
    * Summarising Results of Correlation between Predictors
    * Correlation Analysis Between Response and Predictors
    * Important Findings

3. Regression Model Development
    * Stepwise Feature Selection with Cp, adj_R^2 and BIC
    * Ridge Regression (L1)
    * Lasso (L2)
    * Comparing Results of Stepwise Selections and Parameter Shrinkage

4. XGBoost 
    * Cross-Validation for XGBoost
    * XGBoost Hyper-Parameter Tuning with Grid-Search
    * Assessing Feature Importance

5. Model Comparison


## Key Achievements
Achieved to predict the critical temperature with ± 9.7°K RMSE using XGBoost regression trees
whereas the <a href="https://arxiv.org/pdf/1803.10260.pdf" target="_blank">the state-of-art model</a> for this task achieves ± 9.5°K RMSE.
