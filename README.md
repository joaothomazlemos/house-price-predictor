# house-price-predictor

This is an exercise proposed by Kaggle. For this task, we need to predict houses prices with linear regression.

To achieve better results, I did some data engineering by treating outliers, missing data,  colinearity and data transformations as
we encouter high correlated data with a significant level of skewness.

Then, I trained and tested the data against some of the most popular regression models, using least squares (r2) as scoring metric.
At last, I found that linear Ridge regression model was best suited, with train score of 94% and test score of 92%
