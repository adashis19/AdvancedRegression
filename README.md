# Project - House Price Prediction Model
> The client is looking at prospective properties to buy to enter the Australia market.
A regression model using regularisation is built in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.

- Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal 
The model will  be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
- Ridge Regression with alpha as 6.59 came as the best predictor model, with training set R2 as 89% and test set R2 as 87%.
- The top 5 predictors from Ridge Regression were - OverallQual, 2ndFlrSF, GrLivArea, Neighborhood_NoRidge and RoofMatl_WdShngl.
- Lasso Regression was close second with 87% and 85% R2 on Train and Test Sets Respectively.
