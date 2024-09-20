# [ML-Python] Customer Churn Prediction

## Project goal
- Analyzing the e-commerce customer churn data, identifying user **patterns that are likely to churn** and giving **suggestions** to the company to reduce churned users.
- Build the **Machine Learning** model for **predicting churned users** (Supervised learning).
- **Sort the users who have churned** based on their behaviors into groups and **describe the distinctions** between them (Unsupervised learning).

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
- **K-Means**

## Dataset
The data set belongs to a leading **online E-Commerce** company. An online retail (E commerce) company wants to know the **customers who are going to churn**, so accordingly they can approach the customer to offer some **promotions**.\
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
### 4. Building classification models with Supervised learning to predict churn users
Select Machine Learning algorithms with training data to learn from and perform training data.
### 5. Evaluate models
Evaluate the performance of each model based on evaluation matrices and select the top performing one.
### 6. Segment churned users with Unsupervised learning
Encoding, normalizating, PCA and applying **K-Means** model to label churned users.
