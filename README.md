# Predict-Future-Sales
CMPE 255 - Group Project

OBJECTIVE : 
For one of the largest Russian software firm "1C Company", we aim to forecast the total sales for every store and every product for one month. 
We have data available from January 2013 to October 2015. This project will focus on utilizing a variety of models to predict sales.

DATASET : 
https://www.kaggle.com/c/competitive-data-science-predict-future-sales

Size of Training Data: 2935849 rows * 6 columns

Size of Test Data: 214200 rows 

Source	Description : All the data files are in the zip competitive-data-science-predict-future-sales in Data/

sales_train.csv -	Daily historical data from Jan 2013 to Oct 2015.

test.csv	-  We Require to forecast the sales for the next month for each shop and item.

items.csv -	Items/products information.

item_categories.csv	- Items categories information.

shops.csv	- Shops information.

IMPLEMENTATION : 
Data Analysis, Data Cleaning, Feature Engineering on Data, Training and Testing of Models is in Predict_Future_Sales_Final_Project.ipynb.
Tried the following Models for Training
1) Linear Regression
2) KNN
3) Random Forest
4) LSTM
5) XGBoost 
6) Ensemble model

CONCLUSION : XGBoost gave best performance.
Submission_CSVs contain the kaggle submissions done for this implementation.



