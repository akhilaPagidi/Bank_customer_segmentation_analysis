

# Banking Transaction Analysis & Customer Segmentation

## 1. Project Overview

This project focuses on analyzing banking transaction data to understand customer behavior, transaction patterns, account balances, and customer segments.

Using Microsoft Power BI, I developed an interactive dashboard to explore customer demographics, transaction trends, and customer value. The project also applies customer segmentation techniques to identify loyal, new, and lost customers.

## 2. Project Objectives

- Analyze customer demographics and geographical distribution.
- Understand transaction patterns and customer spending behavior.
- Identify high-value and frequent customers.
- Segment customers based on transaction activity.
- Analyze customer account balances.
- Identify business trends through interactive dashboards.

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Calculated measures and KPIs |
| Data Modeling | Relationships and analytical model |

## 4. Dataset Description

The project uses banking transaction data covering **August 2016 to October 2016**.

### Dataset Columns

| Column | Description |
|---|---|
| TransactionID | Unique transaction identifier |
| CustomerID | Unique customer identifier |
| CustomerDOB | Customer date of birth |
| CustGender | Customer gender |
| CustLocation | Customer location |
| CustAccountBalance | Customer account balance |
| TransactionDate | Date of transaction |
| TransactionTime | Time of transaction |
| TransactionAmount (INR) | Transaction amount in Indian Rupees |

## 5. Project Workflow

### Step 1: Data Cleaning Using Power Query

- Inspected the dataset and identified missing values.
- Handled null values in customer and transaction fields.
- Corrected data types for numerical and date columns.
- Standardized date and time formats.
- Prepared the dataset for analysis.

### Step 2: Data Modeling

- Created the analytical data model in Power BI.
- Organized customer and transaction information for analysis.
- Used customer IDs to analyze customer-level transaction behavior.
- Created measures and calculated columns using DAX.

### Step 3: DAX Calculations

Created measures to calculate important banking KPIs.

Examples of analytical calculations include:

- Total transactions.
- Total transaction amount.
- Average transaction amount.
- Total customers.
- Average account balance.
- Customer transaction frequency.
- Customer segmentation.
- High-value customer identification.

### Step 4: Customer Segmentation

Segmented customers based on their transaction activity.

**Loyal Customers**
- Customers who performed 3 or more transactions.

**Lost Customers**
- Customers whose last transaction was on or before September 30, 2016.

**New Customers**
- Customers who did not fall into the loyal or lost categories.

Also explored RFM-based customer analysis:

- Recency: How recently a customer made a transaction.
- Frequency: How frequently a customer transacted.
- Monetary: How much a customer spent.

Frequency scoring was explored using transaction-count thresholds.

### Step 5: Dashboard Development

Developed four interactive dashboard sections.

**1. Customer Demographics**
- Total customer overview.
- Gender distribution.
- Customer location analysis.
- Customer age analysis.

**2. Transaction Analysis**
- Total transaction amount.
- Transaction volume.
- Average transaction amount.
- Transaction trends over time.
- Transaction activity by time and date.

**3. Customer Segmentation**
- Loyal, new, and lost customer distribution.
- Customer transaction frequency.
- Segment-wise customer analysis.
- Customer value analysis.

**4. Customer Value & Risk Indicators**
- Customer account balance analysis.
- High-value customer identification.
- Top 10 customers based on transaction value.
- Customer transaction activity analysis.

## 6. Key Business Questions

The dashboard was designed to answer questions such as:

1. How many customers are present in the dataset?
2. Which locations have the highest number of customers?
3. What is the gender distribution?
4. What are the overall transaction trends?
5. Which customers perform transactions frequently?
6. How many customers belong to loyal, new, and lost segments?
7. Who are the top 10 high-value customers?
8. How does transaction activity vary across different dates and times?
9. Which customers have comparatively high account balances?

## 7. Business Insights & Applications

The analysis helps banking businesses:

- Understand customer transaction behavior.
- Identify frequently transacting customers.
- Recognize customers with declining or inactive transaction activity.
- Identify high-value customers for targeted engagement.
- Understand customer distribution across different locations.
- Support customer retention and relationship management strategies.


## 8. Conclusion

This project demonstrates practical skills in Power BI, Power Query, DAX, data modeling, KPI development, and interactive dashboard creation.

By analyzing banking transactions and customer behavior, the project provides insights into customer activity, transaction trends, and customer segmentation that can support data-driven banking decisions.

**Technologies:** Microsoft Power BI | Power Query | DAX

**Project Type:** Banking Data Analytics & Customer Segmentation
