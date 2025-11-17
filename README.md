# KPMG-Analysis-using-Excel

This project focuses on analyzing customer demographics, transactions, and new customer data from the **KPMG Dataset** using **Microsoft Excel**.  
The goal of the project is to derive meaningful business insights and provide strategic recommendations based on customer behavior, sales trends, and customer lifetime value (CLV).

## Project Overview

The project is divided into **six major tasks**, covering data cleaning, segmentation, transaction analysis, new customer insights, CLV calculation, and executive recommendations.

The analysis helps the business:
- Understand customer profiles  
- Identify high-value customers  
- Detect sales patterns  
- Explore potential new customer markets  
- Recommend actionable business strategies
  

# 🗂️ Datasets Used

The KPMG dataset consists of four main tables:

### 1. Customer Address Dataset
Contains customer locations and property valuations.  
Key columns: customer_id, address, postcode, state, property_valuation.

### 2. Customer Demographic Dataset
Includes personal details, job information, and purchasing history.  
Key columns: wealth_segment, gender, job_industry_category, DOB, tenure.

### 3. Transactions Dataset
Contains purchase information such as dates, products, and prices.  
Key columns: transaction_id, transaction_date, brand, product_line, list_price.

### 4. New Customer List Dataset
Information about potential new customers.  
Key columns: job_title, property_valuation, wealth_segment, Rank, Value.



#  Tasks Completed

##  Data Cleaning
Performed extensive cleaning to prepare all datasets for accurate analysis:

## Customer Address Data
- Removed duplicates  
- Standardized state names  

##  Customer Demographic Data
- Corrected gender inconsistencies  
- Fixed erroneous values (e.g., “default” column)  
- Standardized missing data formats  

## Transactions Data
- Unified date formats  
- Removed incomplete or invalid rows  

## New Customer Data
- Standardized address formatting  
- Corrected job_title and job_industry anomalies  
- Ensured consistent gender representation  

---

## Customer Segmentation

## By Wealth Segment
- Count of customers per segment  
- Average tenure calculated for each segment  

###  By Gender
- Customer distribution  
- Average bike-related purchases (past 3 years)  

###  By Job Industry
- Count of customers in each industry category  
- Wealth distribution within each job industry  


## Transaction Analysis

## Sales Trend Analysis
- Monthly total sales chart  
- Identified seasonal trends & peak sales months  

## Product Performance
- Sales by brand  
- Total sales + average list_price by product_line  

## Customer Purchase Behavior
- Top 10 highest-spending customers  
- Average purchases per customer  


## New Customer Insights

## Demographics
- Distribution by wealth segment & job industry  
- Average past 3-year purchases  

##Location Insights
- Customer distribution by state (mapped)  
- Correlation between wealth segment & property valuation  

## Estimated Potential Revenue
  Calculated based on:
- Bike-related purchase history  
- Customer “Value” score  



##  Customer Lifetime Value (CLV) Analysis

CLV was calculated using
CLV = (Average Purchase Value × Purchase Frequency) × Customer Lifespan


Where:
- **APV (Average Purchase Value)**= Total Revenue ÷ Number of Purchases  
- **Purchase Frequency** = Total Transactions ÷ Unique Customers  
- **Customer Lifespan** = Tenure (from demographic dataset)  

## Segmented CLV Insights
- CLV variations by wealth segment  
- CLV patterns across demographics: gender, industry, tenure  



## Executive Summary & Recommendations

## Key Findings
- Wealth segments showed clear buying behavior differences  
- High-value customers displayed higher purchase frequency & longer tenure  
- Seasonal spikes observed in transaction patterns  
- New customers in high-valuation properties represent strong revenue potential  

## Recommendations
## Personalized Marketing for High-Value Customers
- Loyalty rewards  
- Priority customer support  
- Personalized offers based on purchase history  

## Business Expansion Opportunities
- Target high-growth states  
- Build stronger regional presence  
- Improve delivery & supply chain in high-demand areas  

## Product Strategy Improvements
- Introduce complementary products  
- Use customer feedback to refine product lines  
- Test new product variations with top customers  



