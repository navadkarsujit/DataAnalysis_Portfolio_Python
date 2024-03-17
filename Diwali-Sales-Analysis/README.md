# Diwali Sales Analysis Project

## Overview

The Diwali Sales Analysis Project is aimed at analyzing sales data from a Diwali sales event to extract insights regarding sales performance, customer behavior, and product popularity. Through this analysis, we seek to understand trends, preferences, and factors influencing sales during the Diwali festival.

## Data Source

The dataset used for this analysis is sourced from a CSV file named "Diwali Sales Data.csv". This dataset encompasses details of sales transactions, including customer demographics, product information, order status, and sales amounts.

## Process

### Importing Libraries and Loading Data

This initial step involves importing essential libraries for data analysis and visualization, such as Pandas, NumPy, Seaborn, and Matplotlib. The sales data is then loaded into a Pandas DataFrame from the provided CSV file.

### Data Preprocessing

Data preprocessing plays a vital role in preparing the raw data for analysis. Initially, we inspect the shape and information of the dataset to understand its structure and identify any missing or irrelevant columns. Subsequently, we drop unnecessary columns like 'Status' and 'unnamed1'. We also handle missing values by dropping null rows and convert the 'Amount' column data type to integer for further analysis.

### Exploratory Data Analysis (EDA)

Exploratory Data Analysis involves examining the dataset to derive meaningful insights. We perform various analyses and visualizations to explore different aspects of sales data:

- **Gender Analysis:** We analyze the distribution of sales based on gender, calculating the total sales amount by gender and visualizing it through bar plots.
  
- **Age Analysis:** We segment customers into age groups and analyze sales trends, both in terms of counts and total sales amount, across different age groups.

- **State-wise Analysis:** We investigate sales performance across different states, identifying top states in terms of order count and total sales amount, and visualizing the results using bar plots.

- **Marital Status Analysis:** We examine sales patterns based on marital status, comparing total sales amount between married and unmarried customers for different genders.

- **Occupation Analysis:** We analyze sales performance based on customer occupation, identifying top occupations contributing to sales revenue.

- **Product Category Analysis:** We explore product category preferences, calculating total sales amount for each product category and visualizing the results through bar plots.

- **Product ID Analysis:** We identify the top-selling products based on order count and visualize the results using bar plots.

## Conclusion

Through the Diwali Sales Analysis Project, we gain valuable insights into sales performance, customer behavior, and product popularity during the Diwali festival. These insights can be utilized by businesses to optimize marketing strategies, improve product offerings, and enhance overall sales performance.
