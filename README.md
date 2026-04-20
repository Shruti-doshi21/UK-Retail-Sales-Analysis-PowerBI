# UK Online Retail Sales Analysis | Power BI Dashboard

> **Business Question:** Which customer segments are driving revenue — and which are at risk of being lost?



##  The Problem

A UK-based online retailer had over 500,000 transactions but no clear view of *who* their most valuable customers were, *what* products were actually profitable, and *when* revenue was likely to peak or drop. This dashboard was built to answer those questions and give the business a foundation for smarter retention and stocking decisions.


## 📊 Dashboard Preview

### Overview
<img width="889" height="495" alt="overview correct" src="https://github.com/user-attachments/assets/8d6cf632-6d89-4d02-af0e-27aa14b69905" />

### Product Analysis
<img width="890" height="494" alt="product analysis" src="https://github.com/user-attachments/assets/ae32553f-10ae-4ae6-9f6a-88007ec88b98" />

### Customer Analysis
<img width="893" height="496" alt="Customer Analysis" src="https://github.com/user-attachments/assets/1a66f2ef-a438-42e3-bd92-e79add4b5c17" />

### RFM Segmentation
<img width="887" height="490" alt="RFM Analysis" src="https://github.com/user-attachments/assets/bb152e7b-e4a0-48d9-afa3-ae82828c9059" />


##  Key Business Findings

**1. Repeat customers are the entire business.**
~66% of customers are repeat buyers, and they contribute approximately **90% of total revenue**. One-time buyers are nearly irrelevant to the bottom line — but represent a large untapped retention opportunity.

**2. Revenue is dangerously seasonal.**
Sales spike sharply in Q4 (Oct–Nov), then drop. A business that doesn't plan inventory and marketing around this pattern will either overstock or miss demand entirely.

**3. A small number of products carry disproportionate revenue.**
The top-performing products by revenue are not the same as the top products by volume. High-selling items can be low-margin traps.

**4. Most customers are low-value or one-time.**
RFM segmentation reveals that while "Champion" customers are the most profitable, they are a small minority. The "At Risk" segment — customers who were once loyal but haven't purchased recently — is the highest-value retention target.



##  Business Recommendations

1. **Prioritise "At Risk" customer reactivation.** These customers have high historical spend but declining recency. A targeted campaign (discount, personalised outreach) directed at this segment would have higher ROI than acquiring new one-time buyers.

2. **Build a Q4 inventory plan.** Revenue concentration in Oct–Nov means stockouts or overstock errors are most costly in this window. The revenue trend data here can directly inform procurement timing.

3. **Audit low-volume, high-revenue products.** These are undermarketed. 



##  Tools & Techniques

| Tool | Purpose |
|---|---|
| Power BI | Dashboard design, interactive visuals |
| Power Query | Data cleaning, removing cancelled orders, type conversion |
| DAX | Custom measures (AOV, Repeat Customer %, RFM scoring) |
| Star Schema | Fact table + Date table relationship modelling |

---

## 📁 Data Cleaning Steps

- Removed all cancelled transactions (Invoice IDs starting with 'C')
- Handled null CustomerIDs and blank descriptions
- Converted InvoiceDate to proper datetime format
- Created calculated Revenue column: `Quantity × UnitPrice`
- Filtered to Dec 2010 – Nov 2011 for consistent annual view
- Built a Date Table for time-intelligence functions

---

##  Files in This Repo

| File | Description |
|---|---|
| `PowerBI_Sales_Dashboard.pbix` | Full Power BI file (open in Power BI Desktop) |
| `PowerBI_Sales_Dashboard.pdf` | Static preview of all dashboard pages |
| `README.md` | This file |

---

##  Author

**Shruti Doshi** — Data Analyst  
[LinkedIn](https://www.linkedin.com/in/shruti-doshi-661a443b8) · [GitHub](https://github.com/Shruti-doshi21)

