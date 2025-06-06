## BALAJI FAST FOOD SALES ANALYTICS

## TABLE OF CONTENTS 
 [Project Overview]()

 [Description]() 

 [Problem statement]()
 
 [Objective]() 

 [Key areas analysed]() 

 [Data Source]()

 [Dataset Description]()
 
 [Tools]()
 
 [Methodology]()

 [Data cleaning]()

 [Exploratory Data Analysis (EDA)]()
 
 [Statistical Insights and Data Visualization]() 
 
 [Recommendation]() 

 [Contact]()

## 📖 PROJECT OVERVIEW 
This project explores and analyze transactional sales data of **Balaji Fast Food** from 2022-2023 using Python to uncover insights into product performance, sales trends, staff efficiency, and customer behavior patterns to recommend strategies to improve sales efficiency and profitability.

## 🔍 DESCRIPTION
A Python-based exploratory data analysis (EDA) project on **balaji fast food sales** using pandas,
matplotlib and plotly 

## PROBLEM STATEMENT 
Balaji Fast Food faces challenges in optimizing sales performance due to uneven product demand, varying staff efficiency, and inconsistent revenue patterns throughout the day and week. While certain food items dominate sales, others underperform, potentially leading to inventory inefficiencies. Additionally, peak sales hours are not fully leveraged due to staffing and service gaps. The business relies heavily on cash payments, despite customer openness to digital options. Without data-driven strategies, these issues could limit profitability, operational efficiency, and customer satisfaction.

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

## 📊 DATASET DESCRIPTION 
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

## 📒 METHODOLOGY 
1️⃣ Data cleaning and preprocessing 

2️⃣ Exploratory Data Analysis (EDA)

3️⃣ Statistical Insights and Data Visualization 

4️⃣ Business Recommendation for balaji fast food

## 📌 DATA CLEANING 
To ensure data quality the following preposition steps where performed 

## 1️⃣ Handle missing value 
After examining the dataset which consist of 1000rows and 10 colums, analysis revealed that 107 records of 1000 records in transaction type contain missing value.
To maintain data integrity missing value were identified and replaced with 'Unknown'.

## 2️⃣ Remove duplicate
To prevent data redundancy duplicate records were removed.
The results confirms no duplicate records exist in the dataset.

## 3️⃣ Data Formatting 
To ensure data consistency and accuracy, the date column was converted from object to date format and extracted month from date for monthly analysis.


## 📈 EXPLORATORY DATA ANALYSIS (EDA)

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

## 🔍📝STATISTICAL INSIGHTS AND DATA VISUALIZATION 

1️⃣ **Total Revenue & Quantity Sold**


![Screenshot](Screenshot_20250605-144144.jpg)


**Total Revenue: 275,230**

**Total Quantity Sold: 8,162 items**


2️⃣ **Sales Trends Overtime**

![Screenshot](Screenshot_20250605-041252.jpg)

✅ **Best Month: September 2022 – 21,340**

✅ **August 2022 was second with -21,285**

❌ **Worst Month: December 2023 – 21,380**


**Peak sales** occurred in **September 2022**, with revenue reaching **21,340**. This represented a monthly revenue peak that declined by over **93%** to **1,380** by December **2023.**




3️⃣ **Quantity by item**

![Screenshot](Screenshot_20250605-041401.jpg)


**Cold Coffee (1,361 units)** and **Sugarcane Juice (1,278 units)** were the top 2 selling items, contributing **32.3%** of total volume, suggesting **strong customer preference**



4️⃣ **Sales by Transaction type**

![Screenshot](Screenshot_20250605-041417.jpg)

Over **88%** of transactions were traceable by type. **Cash** accounted for **48.3%** of sales **(132,840)**, while **Online payments** were **40.2%** **(110,595).**




5️⃣ **Sales by Time of day**

![Screenshot](Screenshot_20250605-041434.jpg)

**Night sales** outperformed all other time slots, generating nearly **62075** or **22.6%** of total revenue.



6️⃣ **Sales by Staff**

![Screenshot](Screenshot_20250605-041502.jpg)



**Mr.** handled **143,440 (52.1%)** of revenue, compared to **Mrs.** with **131,790 (47.9%)**.


## ✅ RECOMMENDATION 
1️⃣ **Extend Night-Time Operations:** Consider extending business hours, launching late-night combo deals, or offering exclusive night-time discounts.

2️⃣ **Focus on Beverage Promotions:** Offer combo deals pairing beverages with fast foods. Create seasonal beverage bundles to boost average order value.

3️⃣ **Promote Digital Payments**: Encourage UPI/QR code payments with small cashback, stamps, or discounts to reduce cash handling and boost efficiency.

4️⃣ **Investigate Post-Peak Revenue Decline:** Conduct surveys, check competitor activity, and review marketing strategies to understand declining trends.

5️⃣ **Implement Staff-Level Sales KPIs:** Track sales per employee per shift. Offer incentives like "Top Seller of the Month" or product upsell bonuses.

6️⃣ **Improve Data Collection Consistency:** Implement POS validation to require payment type input, ensuring more reliable analytics in the future.


## 📞 Contact 
Created by **Ajirola Amudat**  
For inquiries, connect on [LinkedIn](https://www.linkedin.com/in/ajirola-amudat-a-3083882b2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

![Screenshot](Screenshot_20250311-144911.jpg)


