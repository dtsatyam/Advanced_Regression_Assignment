# Advanced Regression Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market.
The company wants to know:
    -  Which variables are significant in predicting the price of a house, and
    -  How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Step 1: Data Preparation<br>
Step 2: Exploratory Data Analysis<br>
Step 3: Data Pre Processing<br>
Step 4: Split data (train & test) & Scale variables<br>
Step 5: Model Building with Ridge & Lasso<br>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Observations:

By comparing both model performance, the train data result on ridge and lasso are performing almost same. R2 for Ridge is: 0.9178 and for Lasso is: 0.9183 And for test data, R2 for Ridge is: 0.8727 and for Lasso is: 0.8714

Below are the top 10 features in Ridge Regression with high beta coefficients:

'GrLivArea',<br>
'TotalBsmtSF',<br>
'OverallQual',<br>
'GarageQual',<br>
'Neighborhood_NoRidge',<br>
'OverallCond',<br>
'GarageYrBlt_2008.0',<br>
'Fireplaces',<br>
'Exterior2nd_CmentBd',<br>
'Neighborhood_Somerst'<br>

Below are the top 10 features in Lasso Regression with high beta coefficients:

'GrLivArea',<br>
'TotalBsmtSF',<br>
'GarageQual',<br>
'OverallQual',<br>
'Exterior2nd_CmentBd',<br>
'Neighborhood_NoRidge',<br>
'OverallCond',<br>
'GarageYrBlt_2008.0',<br>
'Neighborhood_Somerst',<br>
'Fireplaces'<br>

Below are the features that are highly correlated with SaleData

-  Positively correlated with OverallQual (0.79)
-  Positively correlated with MasVnrArea (0.47)
-  Positively correlated with ExterQual (0.68)
-  Positively correlated with BsmtQual (0.64)
-  Positiveely correlated with TotalBsmtSF (0.61)
-  Positiveely correlated with 1stFlrSF (0.61)
-  Positiveely correlated with GrLivArea (0.71)
-  Positively correlated with FullBath (0.58)
-  Positively correlated with KitchenQual (0.65)
-  Positively correlated with TotRmsAbvGrd (0.55)
-  Positively correlated with GarageCars (0.64)
-  Positively correlated with GarageArea (0.62)
-  Negetively correlated with AgeOfHouse (0.5)
-  Best Alfa value using Ridge regression is: 0.9
-  Best Alfa value using Lasso regression is: 0.00001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - 1.21.5
- pandas - 1.4.2
- matplotlib - 3.5.1
- seaborn - 0.11.2
- python - 3.7

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to
- https://www.geeksforgeeks.org/
- https://pandas.pydata.org/
- https://seaborn.pydata.org/
- https://stackoverflow.com/


## Contact
Created by 
- Satyanaraya D
> [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/dtsatyam) 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->