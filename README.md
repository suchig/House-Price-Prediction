# Housing Price Prediction

## Before we proceed
If you are not able to view the ipynb file through github, try using [this nbviewer version](https://nbviewer.jupyter.org/github/suchig/House-Price-Prediction/blob/master/House%20Price%20prediction.ipynb)
## Goal:
To identify the best model that could predict house prices in King County using data provided. 

## Data:
https://www.kaggle.com/harlfoxem/housesalesprediction

## Approach:
- Analyzed the features for potential cleansing
- Split the data into training and test samples
- Applied the following models and identified r2 and MSE values in the training set
  - Linear Regression
  - Lasso
  - Ridge
  - Decision Tree
  - Random Forest
  - XGBoost
- Used hyperopt for hyper parameter tuning
- Predicted using the models and derived r2 and MSE values 
- Created a Residual plot for each prediction. 
- Identified XGBoost as the clear winner based on all results

