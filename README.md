# Credit-score-classification-80-score-7-models
Given a person’s credit-related information, build a machine learning model that



## About Dataset 
### [Problem Statement](https://www.kaggle.com/datasets/parisrohan/credit-score-classification)
> **You are working as a data scientist in a global finance company. Over the years, the company has collected basic bank details and gathered a lot of credit-related information. The management wants to build an intelligent system to segregate the people into credit score brackets to reduce the manual efforts.**

### Task
**Given a person’s credit-related information, build a machine learning model that can classify the credit score.**

* **ID**         : Represents a unique identification of an entry
* **Customer_ID**           : Represents a unique identification of a person
* **Month**             : Represents the month of the year
* **Name**               : Represents the name of a person
* **Age**                 : Represents the age of the person
* **SSN**                   : Represents the social security number of a person
* **Occupation**            : Represents the occupation of the person
* **Annual_Income**         : Represents the annual income of the person
* **Monthly_Inhand_Salary** : Represents the monthly base salary of a person
* **Num_Bank_Accounts**     : Represents the number of bank accounts a person holds


### Credit score Data Modeling

* [importing the libraries](#importing-the-libraries)
* [Reading the data](#Reading-the-data)
* [Exploring the data](#Exploring-the-data)
* [Edit columns and Data Type](#Edit-columns-and-Data-Type)
* [Missing data](#Missing-data)
* [Detect Outliers and Fill NaN Values for Every columns](#Detect-Outliers-and-Fill-NaN-Values-for-Every-columns)
* [SSN](#SSN)
* [Monthly_Inhand_Salary](#Monthly_Inhand_Salary)
* [Num_of_Delayed_Payment](#Num_of_Delayed_Payment)
* [Changed_Credit_Limit](#Changed_Credit_Limit)
* [Num_Credit_Inquiries](#Num_Credit_Inquiries)
* [Credit_History_Age](#Credit_History_Age)
* [Amount_invested_monthly](#Amount_invested_monthly)
* [Monthly_Balance](#Monthly_Balance)
* [Occupation](#Occupation)
* [Type_of_Loan](#Type_of_Loan)
* [Credit_Mix](#Credit_Mix)
* [Payment_Behaviour](#Payment_Behaviour)
* [Age](#Age)
* [Annual_Income](#Annual_Income)
* [Num_Bank_Accounts](#Num_Bank_Accounts)
* [Num_Credit_Card](#Num_Credit_Card)
* [Interest_Rate](#Interest_Rate)
* [Num_of_Loan](#Num_of_Loan)
* [Delay_from_due_date](#Delay_from_due_date)
* [Outstanding_Debt](#Outstanding_Debt)
* [Credit_Utilization_Ratio](#Credit_Utilization_Ratio)
* [Total_EMI_per_month](#Total_EMI_per_month)
* [Save process DATA to CSV](#Save-process-DATA-to-CSV)
* [Drop unimportant columns](#Drop-unimportant-columns)
* [Encoding categorical features](#Encoding-categorical-features)
* [Scaling and Split the data](#Scaling-and-Split-the-data)
* [Model](#Model)
* [Logistic Regression](#Logistic-Regression)
* [KNN](#KNN)
* [Decision Tree](#Decision-Tree)
* [Random forest](#Random-forest)
* [XGBOOST](#XGBOOST)
* [adaboost](#adaboost)
* [Voting](#Voting)
* [compersion between models](#compersion-between-models)

