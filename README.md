
# DQLab Sport Center Data Analysis
## Code and Resources Used
- Python Version: 3.6
- Packages: pandas, matplotlib, seaborn, numpy, sklearn
- Dataset : https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/data_retail.csv
- Case Study : DQLab

## Data Preparation
- Read in data (data_retail.csv) from working directory 

## Data Cleaning
- Change the Data Types First Transaction & Last Transaction Columns (int64 to datetime)
- Check the last transaction in the dataset
- Classifying Customers (Churn or Not Churn) with Boolean.
  The customers is no longer called a customers (Churn) when they are no longer transacting to the shop until the last 6 months from the last transaction.
- Remove no and No_Rows Columns 

## Data Visualization
<img src="Images/Customer%20Acquisition%20Trends%20by%20Year.png" width="300" heigh="300">

<img src="Images/Total%20Transactions%20by%20Year.png" width="300" heigh="300">

<img src="Images/Average%20Transactions%20by%20Year%20for%20Each%20Product.png" width="300" heigh="300">

<img src="Images/Customer%20Distribution%20by%20Count%20Transaction%20Group.png" width="300" heigh="300">

<img src="Images/Customer%20Distribution%20by%20Average%20Transaction%20Amount%20Group.png" width="300" heigh="300">

## Machine Learning Modelling

