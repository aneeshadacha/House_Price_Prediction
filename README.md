# House-Price-Prediction
## Overview
This project focuses on predicting housing prices using Linear Regression with two approaches:

Regularized Gradient Descent
Regularized Normal Equation
The dataset contains various features of homes, and the goal is to predict the housing prices using these features. Regularization techniques are applied to avoid overfitting and improve model performance. The project also compares the accuracy of predictions using both methods and evaluates their effectiveness in terms of the error margin.
## Data Preprocessing
The dataset is preprocessed by:

Removing Unnecessary Columns:
Some columns, such as Unnamed: 0, driveway, recroom, etc., are not relevant for the prediction task and are removed for efficiency.
Normalization:
The features in the dataset are normalized by subtracting the mean and dividing by the standard deviation to ensure all features are on a similar scale.
## Model Building
Regularized Gradient Descent
In this approach, Gradient Descent is used to minimize the cost function while incorporating regularization. The regularization term helps in preventing overfitting and improving the model's generalization ability.

Regularized Normal Equation
The Normal Equation method is used to find the optimal model parameters (theta) by directly computing the solution using matrix operations, without the need for iterative optimization.

## Model Evaluation
Error Computation
The model's prediction accuracy is evaluated using the Mean Absolute Percentage Error (MAPE). This metric helps in understanding the relative error between the predicted and actual prices.

## Error vs Lambda
The project also evaluates how the error changes with different values of the regularization parameter lambda. This helps in identifying the optimal lambda that minimizes the error while avoiding overfitting.

## Visualization
Error vs Lambda Graph
A graph is plotted to visualize how the error changes as the lambda value increases. This helps in understanding the effect of regularization on the model's performance and allows us to identify the optimal lambda value for the best predictions.
