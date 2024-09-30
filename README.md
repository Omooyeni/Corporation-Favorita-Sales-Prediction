# Corporation-Favorita-Sales-Prediction
To build machine learning models to predict the unit sales for thousands of items sold at different Corporation Favorita stores.

# Project Overview
This project aims to predict the unit sales for thousands of items sold at various Corporation Favorita stores. The goal is to build machine learning models that can accurately forecast future sales, helping the company optimize inventory, reduce waste, and improve profitability.

# Dataset
The dataset is provided by Corporation Favorita and includes historical sales data for multiple items across different stores

# Project Objectives
Data Exploration and Preprocessing: Understand the dataset, data cleaning and feature engineering to make the data suitable for machine learning models.

Model Building: Train various machine learning models such as: 

Linear Regression
AutoRegressive Intergrated Moving Average(ARIMA)
Gradient Boosting (XGBoost)

Model Evaluation: Evaluate models using metrics like Root Mean Squared Error (MSE), (RMSE) and choose the best performing model.

Model Tuning: Perform hyperparameter tuning on XGBoost further improve model accuracy.

Prediction: Use the optimized model to predict future sales.

# Project Steps
1. Data Exploration
Analyze the dataset to understand trends and patterns using visualiztions.
2. Data Preprocessing
Handle missing values.
Engineer features from dates (week, month,quater and year).
Encode categorical features.
Scaling.
3. Model Training
Train and validate models using a time-series split to maintain the temporal structure of the data.
Compare model performance based on RMSE, MSE, and MAE.
4. Model Tuning and Optimization
Use grid search and random search to optimize hyperparameters.
Evaluate models on the validation set to avoid overfitting.
5. Final Predictions
Use the best model (XGBoost) to make predictions for future sales.
Compare the predicted sales against actuals for final evaluation.

# Results and Conclusion
The model can now be used to predict sales at Corporation Favorita stores, potentially aiding in inventory management and operational decision-making.
