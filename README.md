# [Multicollinearity in Regression Analysis](#multicollinearity-in-regression-analysis)

## Problem

Multicollinearity is problem that you can run into when you’re fitting a regression model. Simply put, multicollinearity is when two or more independent variables in a regression are highly related to one another, such that they do not provide unique or independent information to the regression.

## How to solve

Using Variance Inflation Factor- VIF- we can determine if two independent variables are collinear with each other. When measuring, if the two features have a VIF of 1, then they are not collinear of each other (ie there are no correlation between these two features). However, as the numbers increases, the higher they are correlated with each other. If VIF returns a number greater than 5, then those two features should be reduced to one using PCA.
