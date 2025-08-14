Project Summary

This project presents a comprehensive data science study using real estate data obtained from Kaggle. It involves both predicting house sale prices based on property features and analyzing market trends through time series modeling.

Project Workflow:

Data Exploration and Preprocessing: The project began with the provided train.csv and test.csv datasets. During this phase, missing values were imputed, outliers were identified and cleaned, and data distribution was improved using methods such as logarithmic transformation.

Feature Engineering: New features such as TotalSF (total square footage), Age (age of the house), and RemodAge (age since last remodel) were created to extract more meaningful insights from the existing columns. These new features were analyzed for their impact on house prices.

Machine Learning Models: Regression models like Lasso and Ridge were applied for house price prediction. Hyperparameters were optimized using GridSearchCV, and model generalizability was evaluated via K-Fold Cross-Validation. The Lasso model achieved the best performance with a low RMSE (Root Mean Squared Error) of approximately 0.1124.

Time Series Analysis: To examine how house prices change over time, a time series was constructed based on monthly average sale prices. Stationarity was checked using the ADF test, and the SARIMA model was applied to capture trends and seasonal effects. This model enabled forecasting future real estate price trends.

By successfully applying all the core steps of a data science workflow (data cleaning, feature engineering, modeling, and analysis), this project provides a comprehensive solution that delivers both real-time price predictions and future trend insights for the real estate market.
