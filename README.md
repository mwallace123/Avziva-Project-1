Happy Customers

Introduction

An anonymous global expansion company wants to determine what makes their customers happy given their services.  The following 6 metrics as outlined in the data description were used as possible determinants as to what makes customers happy. The following project investigates tabulated data where each row represents a single customer and the columns represent the customer's evaluation based on various metrics outlined below. The goal is to create a classification algorithm that reaches 73% accuracy score or above in determining what makes a customer happy based on the six attributes given from the data.

Data Description

Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers

X1 = my order was delivered on time

X2 = contents of my order was as I expected

X3 = I ordered everything I wanted to order

X4 = I paid a good price for my order

X5 = I am satisfied with my courier

X6 = the app makes ordering easy for me

Structure

1. The modules were imported and the data was read and cleaned.
2. EDA analysis was done on each of the six attributes and the target variable including visualizations.  The classes within the target variable were evenly distributed.
3. Correlations were explored between each variable to avoid co-variance in the algorithms.
4. A Correlation matrix was visualized.
5. Introduction of three different machine learning algorithms in the form of functions used throughout the notebook.  These machine learning algorithms were the logistic regression, decision tree and random forest.
6. The data was split into training and testing at various test and train sizes to determine the optimal ratio between the amount of training and testing data using all three algorithms.
7. SHAP values were used to determine the order of the strongest determining variable to the weakest.

Conclusion

The random forest with a 15% testing data and 85% training data performed the best at 89% with an ROC score of 89%.  The algorithms didn't perform above 73% because there was not enough data in the training set.

