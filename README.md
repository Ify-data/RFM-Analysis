# RFM Analysis for Customer Segmentation
RFM (Recency, Frequency, Monetary) Analysis is a powerful technique used by businesses to segment and understand their customers based on their transaction behavior and value. This repository contains a Python script that performs RFM analysis on customer transaction data, helping businesses optimize their marketing strategies and customer engagement efforts.

## Table of Contents
* Introduction
* Analysis
* Results
* Contributions

## Introduction
RFM Analysis is a customer segmentation technique that focuses on three key dimensions: Recency (time since last purchase), Frequency (number of purchases), and Monetary Value (total purchase amount). By categorizing customers based on these metrics, businesses can gain insights into customer behavior and tailor their strategies accordingly.
The script reads customer transaction data from a CSV file. The data includes customer IDs, purchase dates, transaction amounts, and other relevant information.

## Analysis
The following steps were taken:

* Reading and preprocessing the customer transaction data
* Calculating recency, frequency, and monetary values for each customer
* Assigning scores to recency, frequency, and monetary values based on predefined scoring criteria
* Calculating the RFM score for each customer
* Segmentation of customers into different categories and value segments based on their RFM scores

## Results

* RFM scores for each customer
* Customer categories based on RFM scores (e.g., Champions, Loyal Customers, At Risk, etc.)
* Customer value segments (Low Value, Mid Value, High Value)
  
The results are exported to a CSV file (RFM_Analysis.csv) for visualization.

Contributions
Contributions to this project are welcome. If you find any issues or improvements, feel free to open a pull request.
