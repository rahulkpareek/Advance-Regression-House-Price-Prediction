# Project Name
> Advance Regression Techniques Assignment - House Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the 'train.csv' attached.

- The company is looking at prospective properties to buy to enter the market. The aim of the study is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Conclusions
The best value for lambda for both Ridge and Lasso is:
- Ridge - 10
- Lasso - 0.0004

The Mean Squared error is:
- Ridge - 0.01548
- Lasso - 0.01566

The R2Score for train and test set are:

- Ridge
  - R2score for Train set: 0.9262
  - R2score for Test set: 0.8832

- Lasso
  - R2score for Train set: 0.9254
  - R2score for Test set: 0.8820


<b>NOTE</b>
The most significant features that can be suggested to the Surprise Housing company are as follows.

- SaleCondition (either Partial or Normal)
- Neighborhood (specially Crawford)
- Foundation (If it is Poured Concrete)
- Exterior1st (If the exterior covering of the house has a brick face)
- OverallQual
- MSZoning (If in Floating Village Residential Zone)
- OverallCond
- Exterior2nd (If there is a second material used i.e.. Wood siding)
- BsmtExposure (If it has good exposure)


## Technologies Used
- Pandas
- Numpy
- Matplotlib
- Seaborn
- SKlearn

## Acknowledgements
Give credit here.
- This project was inspired by a case study from the Executive PG Programm in Machine Learning by IIIT Bengaluru


## Contact
Created by [@rahulkpareek] - feel free to contact me!
