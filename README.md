# Maven_Northwind_Traders_Sales_Performance_Analysis
Maven Analytics Challenge: I'm working as a BI Developer for Northwind Traders, a global import and export company that specializes in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers around the world (*The picture below is gotten from OutSystems Website*). 

![](https://www.outsystems.com/Forge_CW/_image.aspx/Q8LvY--6WakOw9afDCuuGWJZr_aUfmcmCS7P-ESVEKo=/northwind-db-2023-01-04%2000-00-00-2024-02-26%2009-48-44)


## Introduction

This is an analysis of the sales performance of Northwind Traders. It is done by analyzing data from customers table, employees table, categories table, products table, orders table, order details table, and shippers table. I used Excel to get an overview of the dataset before importing it into Power BI where the actual analysis was carried out. 

## Problem Statement

The goal of this analysis is to:

- Determine noticeable sales trends over time
- Know which are the best and worst selling products
- Identify the company's key customers
- Determine shipping costs across providers
- Finally, the goal is to create data-driven plans that can aid in increasing sales, improving customer satisfaction, and driving the company's growth

## Skills and Concepts Demonstrated:

- Power BI concepts like:
   - Creating key performance indicators (KPIs) and other business calculations
   - Developing general DAX calculations that deal with text and numbers,
   - Performed advanced DAX calculations for solving statistical measures and other mathematical formulas,
   - Data Modelling,
   - Measures,
   - Filters,
   - Tooltips,
   - Page buttons,
   - Data visualization
 
   ---
  ## Data Source:
  
The dataset for the work is gotten from Maven Analytics while its original source is from Microsoft licensed by Public Domain. It consist of 2,985 records and 28 fields of data. I studied the dataset well and its attached dictionary to gain proper insight into the dataset. You can find a link to download the dataset [here:](https://mavenanalytics.io/challenges/maven-northwind-challenge/24)

   ---

## Data Transformation:

The dataset were imported into Power BI as CSV files 
The tables and views are:

- General dataset
 ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/4415e3eb-a839-417e-84d9-e5cc3f6497ea)

- Shippers Table
 ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/87baab31-3a8f-45b0-bcd6-abcf804746ae)

- Products Table
  ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/df5ef89b-03e0-4fbe-b5ec-697662307981)

- Orders Table
  ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/44b1f371-9a75-47ad-bb2f-182085a69b1a)

- Order_details Table
  ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/8c098d0c-7f1e-4dd4-b03b-e191bc67ecc4)

- Employees Table
  ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/42db2c3c-acbd-4e31-a1b4-c3fafc4b3a4c)

- Categories Table
  ![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/36549d49-d8dc-4385-b278-aa7bbce1f684)

I transformed the data in Power Query, checked for Column quality, consistent or appropriate data types.

I began writing several DAX and creating measures and calculated columns to get the right metrics for the Sales Performance analysis.

---

## Data Modelling:

Tables were automatically joined by creating relationships with them, Power BI does this intelligently. However, as someone that understands the dataset and want to get specific insights and information, I had to create other relationships and measures to enable me derive desirable results. Below is the is the created model:

![image](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/329733f3-6b5a-4968-ad84-5666a9664955)

## Data Analysis and Visualization:

Several expressions and functions were made to arrive at the desired KPI or Metrics.
I arrived at a report with a single dashboard consisting of different visuals such as bar chart, doughnut chart, line chart, slicer, and KPIs, giving the summary of the insights gained into the company's performance.

## Features of the Report:
The dashboard conveys information about the following key areas:
- Revenue
- Order
- Product
- Customer
- Shipping cost
- Country

![Maven Northwind Traders Challenge](https://github.com/RemedyData/Maven_Northwind_Traders-_Sales_Performance_Analysis/assets/137626163/420c0d0f-6882-4843-9309-287718a5a61a)

## Analysis

Summary of the insights gained into the company's performance: 

▪︎A total revenue of £1.27 million was realized between the year 2013-2015.

▪︎With 77 products which Northwind Traders had in stock, they were able to receive 830 orders within the year 2013-2015.

▪︎£64,942 was spent on shipping of products within the year 2013-2015.

▪︎Northwind Traders had a total number of 91 customers from 21 different countries within the year 2013-2015.

▪︎Highest revenue was made in April, 2015 with a sum of £124,000.

▪︎Lowest revenue was made in May, 2015 with a sum of £18,000.

▪︎QUICK-stop happens to be the company with the most highest leads generating a sum of £110,277 for Northwind Traders. 

▪︎Hungry Owl All-Night Grocers happens to be the company with the lowest leads generating a sum of £49,979 for Northwind Traders. 

▪︎Beverages happens to be the product with the highest revenue taking 21.16% of the total revenue.

▪︎Grains and Cereals happens to be the product with the lowest revenue taking 7.56% of the total revenue 

▪︎USA, Germany, Austria happens to be the top 3 countries with the highest revenue. 

▪︎United Package has the highest orders followed by Federal Shipping then Speedy Express.


## Recommendation

- There are no doubts that the business is performing well as there are potential leads within the company yielding higher returns.

- The grains and cereals subcategories are not doing much in sales. Strategies to increase the sales should be made like "discounted bundle-selling" where for any purchase of beverages which happens to be the product with the highest revenue, grains or cereals will be added as an offer in addition to the beverages but at a discounted price which will be cheaper compared to when they are buying the grains or cereals as a stand-alone product.

 - Use database to gather customer feedback to get their experiences about the product or services. This information can be used to identify areas for improvement.

 - Understand Customers purchasing pattern by carrying out an analysis on this. This will tell what customers are buying, when they are buying  and how to promote the goods to the customers.

 - It is suggested that 8 products be discontinued so as increase the company's leverage. 


---

### Thank you for reading.

I am open for data anlalyst role.

Let us have discussion about your company and industry now!
