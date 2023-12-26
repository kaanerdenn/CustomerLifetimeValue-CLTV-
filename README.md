# CustomerLifetimeValue-CLTV-

Customer Lifetime Value (CLTV) Calculation

This repository contains a Python script for calculating the Customer Lifetime Value (CLTV) using a dataset from an online retail store. The CLTV is a critical metric in marketing and business that estimates the total revenue a business can expect from a single customer account throughout their relationship with the business.

Overview

The script processes the provided data to calculate the CLTV for each customer based on their purchase history. It involves data preparation, feature engineering, and segmentation of customers based on their calculated CLTV.

Dataset

The dataset used in this script is online_retail_II.xlsx, which contains transaction records for the year 2009-2010. The dataset includes various attributes like Invoice number, Customer ID, Price, and Quantity.

Features

The script calculates the following features for each customer:

Total number of transactions
Total quantity of products purchased
Total price of products purchased
Average order value
Purchase frequency
Profit margin
Customer value
Customer Lifetime Value (CLTV)
Customer segmentation based on CLTV
Usage

To use this script:

Load your dataset in a similar format to online_retail_II.xlsx.
Ensure the required libraries (pandas, sklearn) are installed.
Run the script to perform the CLTV calculation.
The output will be a DataFrame with CLTV and other calculated metrics for each customer.
Optionally, export the resulting DataFrame to a CSV file for further analysis or reporting.
Function: create_cltv_c

The core of this script is the create_cltv_c function, which takes a DataFrame and an optional profit margin as inputs and returns a DataFrame with CLTV and other related metrics.

Requirements

Python 3.x
Pandas
Scikit-learn (for MinMaxScaler, if needed)
