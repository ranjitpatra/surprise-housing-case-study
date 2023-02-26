# Surprise Housing - House Prices - Advanced Regression Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- The company is looking at prospective properties to buy to enter the market. Need to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
-  Need to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 


## Conclusions
- We have used regularisation techniques like Ridge and lasso to predict the target variable. 
for Ridge, optimal value of alpha is 20.
For lasso, optimal value of alpha is 0.001
- Ridge Regression metric:
R2 score of train set is `0.91`
R2 score of test set is `0.85`
- Lasso metric:
R2 score of train set is  `0.93`
R2 score of test set is `0.84`




## Technologies Used
- python - version 3.9.1
- numpy - version 1.21.5
- matplotlib - version 3.5.2
- seaborn - version 0.11.2
- scikit-learn - version 1.0.2
- jupyter notebook - version 6.5.1





## Contact
Created by Ranjit Patra [@ranjitpatra](https://github.com/ranjitpatra) - feel free to contact me!