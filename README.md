# Housing Price Prediction
 
# Description

This is a kaggle competition. https://www.kaggle.com/c/house-prices-advanced-regression-techniques.

The purpose of this project is to predict house price given a dataset which includes 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa. 
In this project, I used random forest regression, gradient boosting regression, xgboost regression, catboost regression, and lasso regression models and compared their performances. Catboost regression model ended up with the lowest RMSE (Residual Mean Square Error). 

Best Kaggle Score: 0.12324 (equivalent to about top 13.6%)
I slightly changed the code to differentiate the nominal features and ordinal features and this ended up actually lowering my submission score. The current jupyter code will give a score of 1.2468 which is slightly worse than my best submission. However, I believe the prediction can be improved if I perform hyperparatemeter tuning of regression models.
