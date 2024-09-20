# [ML-Python] Customer Churn Prediction

## About
One ecommerce company has a project on predicting churned users in order to offer potential promotions. 
An attached file is the dataset that is offered by the company (churn_predict.csv). You will using these dataset to answer below questions: 
> **Objective**
> 1. What are the patterns/behavior of churned users? What are your suggestions to the company to reduce churned users. 
> 2. Build the Machine Learning model for predicting churned users. (fine tuning) 
> 3. Based on the behaviors of churned users, the company would like to offer some special promotions for them. 
Please segment these churned users into groups. What are the differences between groups? 


## Technology used
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Machine learning algorithms used
- **Logistic Regression**
- **Random Forest Classifier**
- **Decision Tree Classifier**

## Dataset
\
It has the following columns.

|Variable|Description
|---|---|
|CustomerID|Unique customer ID|
|Churn|Churn Flag
|Tenure|Tenure of customer in organization|
|PreferredLoginDevice|Preferred login device of customer|
|CityTier|City tier (1,2,3)|
|WarehouseToHome|Distance in between warehouse to home of customer|
|PreferPaymentMethod|PreferredPaymentMode Preferred payment method of customer|
|Gender|Gender of customer|
|HourSpendOnApp|Number of hours spend on mobile application or website|
|NumberOfDeviceRegistered|Total number of devices is registered on particular customer|
|PreferedOrderCat|Preferred order category of customer in last month|
|SatisfactionScore|Satisfactory score of customer on service|
|MaritalStatus|Marital status of customer|
|NumberOfAddress|Total number of added added on particular customer|
|Complain|Any complaint has been raised in last month|
|OrderAmountHikeFromlastYear|Percentage increases in order from last year|
|CouponUsed|Total number of coupon has been used in last month|
|OrderCount|Total number of orders has been places in last month|
|DaySinceLastOrder|Day Since last order by customer|
|CashbackAmount|Average cashback in last month|

## Features
### 1. Importing and preparing the data 
Loading the data and understanding the features present in it. 
### 2. Processing the data with Exploratory Data Analysis (EDA) 
Perform univariate and bivariate analyses of the data, followed by feature transformations. 
### 3. Splitting the data
Separate the data into three subsets: one for evaluation, one for testing, and one for model training.
### 4. Building classification models 
Select Machine Learning algorithms with training data to learn from and perform training data.
### 5. Evaluate models
Evaluate the performance of each model based on evaluation matrices and select the top performing one.
