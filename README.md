# Logistic_Regression_Classifier


Logistic Regression:

Logistic Regression is a supervised machine learning classification algorithm. It is used to predict the probability of categorical dependet variable. We use that predicted probability for the classification. The dependent variable is a binary variable that contains data coded as 0 and 1 where 1 means success and 0 means failure.

# Why it is called regression?
Since we use it for the prediction of the probability but ultimately it predictes the value that's why we call it regression. 

## Logistic Regression Assumptions

1. Binary logistic regression requires the dependent variable to be binary.
2. For a binary regression, the factor level 1 of the dependent variable should represent the desired outcome.
3. Only the meaningful variables should be included.
4. The independent variables should be independent of each other. That is, the model should have little or no multicollinearity.
5. The independent variables are linearly related to the log odds.
Logistic regression requires quite large sample sizes.


## Logistic VS Linear Regression

It is a special case of linear regression where the target variable is categorical in nature. It uses a log of odds as the dependent variable. Logistic Regression predicts the probability of occurrence of a binary event utilizing a logit function. 
Linear regression gives you a continuous output, but logistic regression provides a constant output. 

An example of the continuous output is house price and stock price. Example's of the discrete output is predicting whether a patient has cancer or not, predicting whether the customer will churn. Linear regression is estimated using Ordinary Least Squares (OLS) while logistic regression is estimated using Maximum Likelihood Estimation (MLE) approach.
