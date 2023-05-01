# housing-price-prediction

This repository contains code for performing a regression analysis for predicting housing prices using linear, ridge, and lasso regression models.

## Data
The dataset used in this analysis can be obtained from Kaggle.

## Analysis
1. Data preprocessing: The dataset was preprocessed by encoding categorical variables, scaling the features, and splitting the data into training, validation, and test sets.
2. Model selection: Three regression models (linear, ridge, and lasso) were selected to predict housing prices.
3. Hyperparameter tuning: GridSearchCV was used to tune the hyperparameters for each of the three models.
4. Model training and evaluation: The models were trained using the training set, evaluated using the validation set, and the best model (Lasso regression) was selected.
5. Model testing: The selected model was then evaluated using the test set.

## Results
The Lasso regression model performed the best based on multiple evaluation metrics (MAE, MSE, RMSE, R2)
