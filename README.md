# [ML-Python] Customer-Churn-Prediction

## About
This project aims to examine **credit card transactions** data and provide insights regarding the **behaviors of fraudulent transactions**. Then, construct a classification ensemble model for **detecting credit card fraud** using **Machine Learning with Python**.

## Technology used
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Machine learning algorithms used
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**

## Dataset
This data set contains the information of **credit card transactions** that are **marked as fraud transactions or not**.\
It has the following columns.
|Column|Meaning|
|---|---|
|trans_date_trans_time|The date and time of the transaction|
|cc_num|Credit card number|
|merchant|Merchant who was getting paid|
|category|In what area does that merchant deal|
|amt|Amount of money in American Dollars|
|first|First name of the card holder|
|last|Last name of the card holder|
|gender|Gender of the cardholder. Just male and female|
|street|Street of card holder residence|
|city|City of card holder residence|
|state|State of card holder residence|
|zip|ZIP code of card holder residence|
|lat|Latitude of card holder|
|long|Longitude of card holder|
|city_pop|Population of the city|
|job|Trade of the card holder|
|dob|Date of birth of the card holder|
|trans_num|Transaction ID|
|unix_time|Unix time which is the time calculated since 1970 to today|
|merch_lat|Latitude of the merchant|
|merch_long|Longitude of the merchant|
|is_fraud|Whether the transaction is fraud (1) or not (0)|

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
