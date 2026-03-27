# Online Retail Sales Analysis Dashboard (Power BI)

## Project Overview
This project is an end-to-end Power BI dashboard built using a UK-based online retail dataset. The goal of the project is to analyze business performance, product trends, and customer behavior to derive meaningful insights for decision-making.


## Objectives
- Analyze overall sales performance
- Identify top-performing products
- Understand customer behavior and retention
- Segment customers using RFM analysis


## Data Cleaning & Preparation
Performed in Power Query:
- Removed cancelled transactions (Invoice starting with 'C')
- Handled missing values
- Converted data types (especially date fields)
- Created a *Revenue column* (Quantity × Unit Price)
- Filtered dataset for *Dec 2010 – Nov 2011*
- Created a *Date Table* for time-based analysis


## Data Modeling
- Created a *Fact Table (fact_sales)*
- Built relationships between:
  - Date Table → fact_sales (Invoice Date)
- Implemented star schema approach


## Key Metrics (DAX Measures)
- Total Revenue
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Repeat Customers %
- Customer-level metrics (Recency, Frequency, Monetary)


## Dashboard Pages

### 1. Overview
- KPI Cards: Revenue, Orders, Customers, AOV
- Monthly Revenue Trend
- Revenue by Country
- Order Trend

*Key Insight:*
- Revenue peaks during Q4, indicating strong seasonality
- Majority revenue comes from the UK


### 2. Product Analysis
- Top Products by Revenue
- Top Products by Quantity
- Product Performance Table

*Key Insight:*
- A small number of products contribute significantly to total revenue
- High-volume products are not always high-revenue products


### 3. Customer Analysis
- Customer Growth Trend
- Repeat vs One-time Customers
- Revenue Contribution by Customer Type
- Top Customers by Revenue

*Key Insight:*
- ~66% customers are repeat buyers
- Repeat customers contribute ~90% of total revenue


### 4. RFM Analysis
- Customer segmentation based on:
  - Recency
  - Frequency
  - Monetary value
- Distribution charts for each metric
- Customer Segmentation (Champions, Loyal, At Risk, etc.)

*Key Insight:*
- Majority customers are low-value or one-time buyers
- Small segment of high-value customers drives major revenue


##  Business Insights
- Strong dependency on repeat customers
- Seasonal spike in sales during year-end
- Revenue concentration among top products and customers
- Opportunity to improve retention of one-time customers


##  Tools & Technologies
- Power BI
- Power Query
- DAX (Data Analysis Expressions)


##  Dashboard Preview
### Overview Page
<img width="889" height="495" alt="overview correct" src="https://github.com/user-attachments/assets/8d6cf632-6d89-4d02-af0e-27aa14b69905" />

### Product Analysis
<img width="890" height="494" alt="product analysis" src="https://github.com/user-attachments/assets/ae32553f-10ae-4ae6-9f6a-88007ec88b98" />

### Customer Analysis
<img width="893" height="496" alt="Customer Analysis" src="https://github.com/user-attachments/assets/1a66f2ef-a438-42e3-bd92-e79add4b5c17" />

### RFM Analysis
<img width="887" height="490" alt="RFM Analysis" src="https://github.com/user-attachments/assets/bb152e7b-e4a0-48d9-afa3-ae82828c9059" />


##  Conclusion
This project demonstrates the ability to transform raw data into actionable insights using Power BI. It highlights key business trends and provides a foundation for data-driven decision-making.


##  Author
Shruti Doshi
