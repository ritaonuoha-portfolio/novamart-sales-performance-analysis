# NovaMart Sales Performance Analysis

## Project Overview

This project analyzes NovaMart sales transaction data to evaluate business performance across sales, profitability, regions, stores, customer segments, and sales channels.

The objective was to transform raw transactional data into meaningful business insights that can support better business decisions.

> **Portfolio Project:** Practice project using a dataset provided through Esther's data analytics community.

---

## Business Questions

The analysis was designed to investigate:

- What are the total sales and profit?
- How do sales change month by month?
- Which months perform best and worst?
- Which regions generate the most revenue?
- Which stores perform best?
- Which customer segments generate the most sales?
- How does Online compare with Physical Store sales?
- What are the major sales and profitability trends?
- Where are potential areas for improvement?

---

## Tools Used

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Excel Data Model
- Data Cleaning & Transformation
- Data Analysis & Visualization

---

## Data Preparation & Cleaning

The data preparation stage involved several data-quality challenges.

### Inconsistent Date Formats

Some date records were stored in different formats, which made automatic date conversion difficult and resulted in date errors.

The affected records were retained rather than deleted simply because of the date issues.

### Missing Values

Missing values were identified in fields such as:

- Customer ID
- Product ID
- Store ID
- Quantity
- Unit Price
- Discount

Where categorical information could not be reliably recovered, missing values were treated as `Unknown`.

Numerical values were not automatically replaced with zero because zero represents an actual value and could distort the analysis.

### Blank Values in PivotTables

Some missing values resulted in `(Blank)` categories appearing in PivotTables and visualizations.

The affected transactions were retained rather than deleted simply to remove the blanks.

---

## Dashboard

https://github.com/ritaonuoha-portfolio/novamart-sales-performance-analysis/blob/main/normart%20dashboard.jpeg

---

## Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Sales** | **$11.62M** |
| **Total Profit** | **$1.91M** |
| **Profit Margin** | **16.5%** |
| **Total Orders** | **2,995** |
| **Quantity Sold** | **8,685** |

---

## Key Insights

### Sales Performance

NovaMart generated approximately **$11.62M in total sales** and **$1.91M in profit**, resulting in an overall **16.5% profit margin**.

### Monthly Performance

**August recorded a significant sales and profit spike**, making it an important period for further investigation.

### Regional Performance

**Asia recorded the strongest regional sales**, followed by Europe and Africa.

### Sales Channel Performance

**Online sales outperformed Physical Store sales**, highlighting the importance of the online channel to NovaMart's overall revenue.

### Customer Segment Performance

**Mass Market** was the strongest-performing customer segment in the dashboard analysis.

### Store Performance

Store performance varied considerably, with some locations significantly outperforming others.

---

## Recommendations

1. **Investigate the August sales spike** to identify the products, customers, regions, or activities that contributed to the increase.

2. **Strengthen the Online sales channel** while identifying opportunities to improve Physical Store performance.

3. **Investigate underperforming stores and regions** and compare their performance with stronger locations to identify improvement opportunities.

4. **Monitor profitability alongside revenue** to ensure that high sales are also translating into healthy profit.

5. **Improve data quality at source**, particularly missing customer and transaction information, to support more reliable customer-level analysis.

---

## Challenges & Learning

One of the biggest lessons from this project was that **data analysis does not begin with the dashboard**.

A significant part of the project involved dealing with inconsistent dates, missing values, blank categories, and unexpected PivotTable results.

These challenges required me to investigate the data, question unexpected results, and make decisions about how missing information should be handled without unnecessarily removing valid transactions.

This project strengthened my understanding of the importance of:

- Data quality
- Data validation
- Data cleaning
- Business context
- Analytical thinking
- Communicating insights

---

## Project Outcome

The final dashboard provides a high-level view of NovaMart's:

- Sales performance
- Profitability
- Monthly trends
- Regional performance
- Customer segments
- Store performance
- Online vs Physical Store performance

The project demonstrates my ability to move from:

**Raw Data → Data Cleaning → Analysis → Visualization → Business Insights → Recommendations**

---

## Key Takeaway

This project taught me that a good data analyst does more than create attractive dashboards.

The analyst must also understand the quality of the data, identify limitations, validate the results, answer relevant business questions, and translate findings into actionable recommendations.

---

## Project Credit

Dataset provided through **Anagu Esther's data analytics community**.
