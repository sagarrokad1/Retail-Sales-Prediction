# Rossman-Sales-Prediction

## PROBLEM STATEMENT

The data set that was provided to us was of Rossmann that operates over
3,000 drug stores in 7 European countries. Rossmann store challenge was to
predict their daily sales for up to six weeks in advance. Store sales are
influenced by many factors, including promotions, competition, school and
state holidays, seasonality, and locality.

So we were provided with historical sales data for 1,115 Rossmann stores and
the task was to forecast the "Sales" column for the test set.

APPROACH

Exploratory Data Analysis: -
We performed exploratory data analysis with python to get insights from the data to
observe following things: -
● Sales were highly correlated to the number of Customers.
● The most selling and crowded store type was A.
● Store Type B had the lowest Average Sales per Customer. So we think
customers visit this type only for small things.
● Store Type D had the highest buyer cart.
● Promo would run only on weekdays.
● For all stores, Promotion would lead to increase in Sales and Customers
both.

Models Implementation: -
1. Linear Regression
Fair Accuracy with low train and test score.
2. Lasso Regression
Fair Accuracy with low train and test score.
3. Decision Tree Regressor
Good train and test score.
4. K- nearest neighbors
Poor train and test score in comparison to other models.
5.Random Forest Regressor
Very good train and test score with good accuracy.
Conclusions: -
The Rossmann Store Sales problem is a very interesting data science problem
to solve. We observed that the problem is more focused on feature
engineering and feature selection than on model selection.
Train score Test score
Linear regression 0.78 0.78
Lasso Regression 0.78 0.78
Decision Tree 0.99 0.91
Decision Tree with
Parameter

0.96 0.93

Random Forest 0.99 0.95

Among all models, Random Forest works the best and provides a reliable
prediction of the sales.
