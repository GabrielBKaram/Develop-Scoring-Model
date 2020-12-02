# Develop-Scoring-Model

In this notebook, I will build a classification model that predicts whether the client will default on the repayment of their loans or not.

I will perform an extensive EDA and then start with building a simple logistic regression. I will then perform feature engineering and feature selection in order to trim down the number of features to be used in the analysis. I will build a random forest classifier with the new features and apply RandomizedSearchCV for hyperparameter tuning.

The final aim is to see which model will perform best between the logistic regression and the random forest classifier in predicting whether the client will default or not.
