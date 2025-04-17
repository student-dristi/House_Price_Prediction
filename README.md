# House_Price_Prediction
# House Price Predictor using Linear Regression Model
A simple machine learning project using Linear Regression to estimate housing prices based on features from the Boston Housing dataset.

#Dataset
The dataset used is the classic Boston Housing dataset, which contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.

#Features used:
rm: average number of rooms per dwelling

zn: proportion of residential land zoned for large lots

lstat: percentage of lower status population

#Target:
medv: Median value of owner-occupied homes in $1000s

#Model
We use Linear Regression from sklearn.linear_model to predict house prices.

Steps:
Load and clean the dataset (handle missing values)

Visualize correlations using a heatmap

Split data into training and testing sets

Train the Linear Regression model

Evaluate performance using R² Score
