# Housing Price Prediction

# Objective
The main objective of this project is to predict house prices in Ames, Iowa using machine learning algorithms.

# Description
This is a kaggle competition. https://www.kaggle.com/c/house-prices-advanced-regression-techniques.

* Feature Engineering
** Imputate missing values using median (numerical) and mode (categorical) values
** Identify most important features via correlation values
** Separate and encode nominal and ordinal features
** Visualize the distribution of each feature and perform log or box-cox transformation to fix skewness/heteroscedasticity
* Compare the performance of RandomForestRegressor, GradientBoostingRegressor, XGBoostRegressor, CatBoostRegressor, and LassoRegressor via RMSE

For the sake of time, I did not perform hyperparameter tuning in this project. 

# Result 

Best Kaggle Score: 0.12324 (equivalent to about top 13.6%)
I slightly changed the code to differentiate the nominal features and ordinal features and this ended up actually lowering my submission score. The current jupyter code will give a score of 1.2468 which is slightly worse than my best submission. However, I believe the prediction can be improved if I perform hyperparatemeter tuning of regression models.

# Credits
Credits to several authors of related articles on medium and towardsdatascience.
Unfortunately, this was my first project and I forgot to cite/save the articles.
