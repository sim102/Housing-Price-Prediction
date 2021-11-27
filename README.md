# Housing Price Prediction
## Introduction

In this project, we will predict residential prices in Ames, Iowa. 
79 explanatory variables and 1 response variable, house price, are provided. 

## Methods

Summarized steps for this analysis are following:

1. Examine the types (qualitative or quantitative) and basic informations of the variables.
2. Find the most correlated varialbes and visualize them with respect to the SalePrice, our response variable.
3. Use various transformation methods and find the most appropriate one to make the variables normally distributed.
4. Perform data cleaning and feature engineering.
5. Utilize cross-validation models (base models) and blend them to predict the housing prices.

Followed by enhanced visualization, data transformation, cleaning, feature selection and engineering, several regression models have been performed.

Ridge, Lasso, Gradient Boosting Regressor and others have been utilized as base models and stacked model with meta-regressor (xgboost) has been included.

Then, we blended the model with base and stacked models, with corresponding weights.

## Results

Each Base models displayed about 0.09 ~ 0.1 RMSE.

Blending process decreased the RMSE by about 50%, achieving 0.05 RMSE in the end.


