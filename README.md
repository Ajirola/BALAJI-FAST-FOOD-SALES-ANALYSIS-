## BALAJI FAST FOOD SALES ANALYSTICS

## TABLE OF CONTENTS 
 [Project Overview]()

 [Description]() 
 
 [Objective]() 
  
 [Key areas analysed]() 

 [Dataset Overview]()
 
 [Tools]()
 
 [Methodology]()

 [Data cleaning]()
 
 [Insights]() 
 
 [Recommendation]() 

## 📖 PROJECT OVERVIEW 
This project explores and analyze transactional sales data of **Balaji Fast Food** from 2022-2023 using Python to uncover insights into product performance, sales trends, staff efficiency, and customer behavior patterns.

## 🔍 DESCRIPTION
A Python-based exploratory data analysis (EDA) project on **balaji fast food** using pandas,
matplotlib and plotly 

## 🎯 OBJECTIVE 
This analysis aims to answer the following business question:

1️⃣ **How do sales trend over time?**

2️⃣ **What are the most and least popular items?**

3️⃣ **What are the preferred payment methods?**

4️⃣ **What time of day generates the most revenue?**

5️⃣ **Which staff members are driving the highest sales?**

## 🔍 KEY AREAS ANALYZED
The analysis of Balaji Fast Food's sales data focused on the following critical areas:

1️⃣ **Product Performance** - Identified top-selling and least-selling menu items

2️⃣ **Staff Performance** - Compared performance across staff members

3️⃣ **Sales Trends Over Time** - Analyzed sales volume over different time of the day and Identified peak and off-peak periods

4️⃣ **Customer Behavior** - Assessed preferences based on item popularity 

5️⃣ **Payment and Transaction Methods** - Identified the most common transaction method

## 📊 DATA SOURCE
The data was obtained from kaggle website
Here's the link to the dataset: https://www.kaggle.com/datasets/rajatsurana979/fast-food-sales-report

## 📊 DATASET OVERVIEW
The data consist of 1000 records with 10 columns.

✅ **Order_ID**: Unique identifier assigned to each transaction

✅ **Item_Name**: Name of the food or beverage item purchased

✅ **Item_Type**: Category of the item (`Fast Food`, `Beverage`)

✅ **Item_Price**: Price per unit of the item

✅ **Quantity**: Number of units purchased in the transaction

✅ **Transaction_Amount**: Total amount paid by the customer (Quantity × Item_Price)

✅ **Transaction_Type**: Mode of payment (`Cash`, `Online` etc.)

✅ **Received_By**: Staff member (including gender) who handled the transaction

✅**Date**: Date when the transaction took place

✅**Time_of_Sales**: Time of the transaction (Morning, Afternoon, Evening, Night)

## ⚒️ TOOLS USED:

Python (Pandas,Matplotlib,Seaborn,Plotly)

Jupyter Notebook 

## METHODOLOGY 
1️⃣ Data cleaning and preprocessing 

2️⃣ Exploratory Data Analysis (EDA)

3️⃣ Statistical Insights and Data Visualization 

4️⃣ Business Recommendation for balaji fast food

## DATA CLEANING 
To ensure data quality the following preposition steps where performed 

## 1️⃣ Handle missing value 
After examining the missing value which consist of 1000rows and 10 colums, analysis revealed that 107 records of 1000 records in transaction type contain missing value.
To maintain data integrity missing value were identified and replaced with 'Unknown'.

## 2️⃣ Remove duplicate
To prevent data redundancy duplicate records were removed.
The results confirms no duplicate records exist in the dataset.

## 3️⃣ Data Formatting 
To ensure data consistency and accuracy, the date column was converted from object to date format (yyyy-mm-dd)

## EXPLORATORY DATA ANALYSIS (EDA)

**Descriptive statistics**
The sales data consists of 1000 records, exhibiting the following character:

**Mean Sales**: **275.23**
**Standard deviation**: **204.40**
**Minimum sales**: **20.00**
**25%(Q1)**: **120.00**
**50%(Median)**: **240.00**
**75%(Q3)**: **360.00**
**Maximum Sales**: **900.00**

1️⃣ Sales ranged from **20.00** to **900.00**, indicating a **wide variation** in customer spending habits.
2️⃣ The average sales value is **275.23**, suggesting that most customers make **moderately** priced purchases.
3️⃣ The smallest recorded transaction was **20.00**, likely reflecting a **single low-cost** item purchase.
4️⃣ 50% of the sales are **240.00**, indicating a **midpoint** sales distribution.

## 🔍📊STATISTICAL INSIGHTS AND DATA VISUALIZATION 
1️⃣ **Sales Trends Overtime**

![Screenshot](Screenshot_20250605_041252.jpg)







## RECOMMENDATION 
1️⃣ **Improve Margin Management for Top Suppliers:** Engage with Two Brothers Mill to explore cost optimization or pricing strategies to improve profitability.

2️⃣ **Scale High-Margin Suppliers:** Increase focus on suppliers like Kappas Drinks for their better return on sales.

3️⃣ **Channel Strategy Optimization:** Strengthen the Online channel, especially for high-performing categories like Drinks.

4️⃣ **Focus on High-Performing Months:** Replicate successful strategies from November to maintain performance consistency.

5️⃣ **Team-Level Strategy:** Analyze and share best practices from high-performing Retail teams across other segments.

## Contact
Created by **Ajirola Amudat**  
For inquiries, connect on [LinkedIn](https://www.linkedin.com/in/ajirola-amudat-a-3083882b2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
