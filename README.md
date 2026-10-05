# ApexPlanet Task 3 — Deep-Dive Analysis

## ApexPlanet Data Analytics Internship

**Task 3: Deep-Dive Analysis, Customer Segmentation & Business Intelligence Dashboard**

This project is part of my ApexPlanet Data Analytics Internship. The objective of Task 3 was to perform a deep-dive analysis of customer behavior, sales performance, customer segmentation, business trends, and business intelligence insights using a cleaned sales dataset.

The project combines analytical outputs, customer segmentation, business insights, and an interactive HTML dashboard designed with a Power BI-style executive layout.
## Live Interactive Dashboard
[View Interactive Dashboard](YOUR_GITHUB_PAGES_LINK)


---

## Project Objectives

- Analyze overall sales and customer performance
- Calculate core business KPIs
- Perform customer-level analysis
- Segment customers based on sales contribution
- Analyze sales by gender, city, category, and product
- Identify top customers
- Analyze monthly sales trends
- Identify important business insights
- Develop actionable business recommendations
- Build an interactive Business Intelligence dashboard

---

## Dataset Overview

| Metric | Value |
|---|---:|
| Total Records | 1,000 |
| Unique Customers | 947 |
| Unique Order IDs | 992 |
| Total Sales | 139,399,439.65 |
| Total Quantity | 5,435 |
| Sales per Customer | 147,201.10 |

The analysis was performed using the cleaned dataset prepared during the previous stage of the internship.

---

## Key Performance Indicators

The major KPIs analyzed in this project include:

- Total Sales
- Total Quantity
- Unique Customers
- Unique Orders
- Sales per Customer
- Average Order Value
- Customer-level sales performance

---

## Customer Segmentation

Customers were segmented based on customer-level Total Sales.

| Segment | Customers |
|---|---:|
| High Value | 237 |
| Medium Value | 473 |
| Low Value | 237 |

### Key Finding

High Value customers contribute approximately **55.27% of total sales**, making customer retention and targeted engagement important business priorities.

---

## Key Business Insights

### Customer Insights
- High Value customers represent a smaller customer group but contribute a major share of total sales.
- Customer-level analysis helps identify important revenue contributors.
- The Top 10 Customers analysis highlights the most valuable customer relationships.

### Category & Product Insights
- Electronics is the highest sales-contributing category, accounting for approximately **36.43% of total sales**.
- Product-level analysis helps identify strong and weaker product performance.

### City Insights
- **Patna** recorded the highest total sales.
- **Bengaluru** recorded the highest sales per customer.

### Monthly Sales Insights
- **March 2025** was the highest-performing full month.
- **September 2025** was the lowest-performing full month.
- **January 2026** is a partial month and should not be directly compared with complete months.

---

## Business Recommendations

Based on the analysis:

1. Prioritize retention strategies for High Value customers.
2. Develop targeted offers and engagement strategies for valuable customer segments.
3. Monitor Electronics performance and identify opportunities for further growth.
4. Analyze lower-performing cities and identify improvement opportunities.
5. Use customer-level insights for targeted marketing and retention.
6. Monitor monthly sales fluctuations to support better business planning.
7. Review repeated Order IDs and Unknown city records as part of ongoing data-quality management.

---

## Interactive Business Intelligence Dashboard

The project includes an **Interactive HTML Business Intelligence Dashboard** designed with a Power BI-style executive layout.

### Dashboard Features

- KPI Cards
- Customer Segmentation
- Monthly Sales Trend
- Category Performance
- Product Performance
- City Performance
- Top 10 Customers
- Segment Analysis
- Interactive Filters
- Business Insights
- Business Recommendations

### Dashboard Filters

The dashboard supports interactive filtering by:

- Date
- City
- Gender
- Category
- Product
- Customer Segment

---

## Data Quality Notes

The analysis identified several data-quality considerations:

- 8 repeated Order ID records were identified.
- Repeated Order IDs were reviewed rather than automatically merged.
- `ORD100050` is an example of a repeated Order ID associated with different records.
- 13 records contain `Unknown` city values.

These records were retained for analysis while being documented as data-quality considerations.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- SQL
- Microsoft Excel
- Power BI / DAX concepts
- HTML
- JavaScript
- Data Visualization
- Business Intelligence

---

## Project Files

### Core Project Files

- `ApexPlanet_Cleaned_Dataset.xlsx`
- `ApexPlanet_Task_3_Deep_Dive_Analysis_Report.pdf`
- `ApexPlanet_Task_3_DAX_Measures_Summary.txt`
- `ApexPlanet_Task_3_Dashboard.pptx`
- `ApexPlanet_Task_3_Interactive_Dashboard.html`

### Analysis Outputs

- `00_Duplicate_Order_IDs.csv`
- `01_Core_KPIs.csv`
- `02_Customer_Analysis.csv`
- `03_Segment_Summary.csv`
- `04_Top_10_Customers.csv`
- `05_Segment_Gender.csv`
- `06_Segment_Gender_Percentage.csv`
- `07_Segment_City.csv`
- `08_Segment_Category.csv`
- `09_Segment_Product.csv`
- `10_Monthly_Segment_Sales.csv`
- `11_Monthly_Sales.csv`
- `12_City_Summary.csv`
- `13_Category_Summary.csv`
- `14_Product_Summary.csv`
- `Deep_Dive_Analysis_Summary.txt`

---

## Project Walkthrough

A project walkthrough video has been created to demonstrate the Task 3 analysis, dashboard, key insights, and business recommendations.

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from cleaned data and KPI analysis to customer segmentation, business intelligence, interactive dashboard development, and actionable business recommendations.

The analysis provides a structured view of customer value, sales performance, product and category contribution, city performance, and monthly business trends.

---

## Internship

**ApexPlanet Data Analytics Internship — Task 3**

**Project:** Deep-Dive Analysis, Customer Segmentation & Business Intelligence Dashboard
