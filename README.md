# Task 13 – BI Dashboard Storytelling (KPI Report)

## Project Overview

This project focuses on building an interactive Business Intelligence dashboard using Power BI. The objective is to analyze retail sales data and present key business insights through effective data visualization and storytelling.
The dashboard helps stakeholders understand sales performance, customer behavior, and product trends, enabling data-driven decision-making.

---

## Objectives

* To create meaningful KPIs using DAX
* To visualize sales trends and category performance
* To identify top-performing customers
* To build an interactive dashboard with filters
* To present business insights through storytelling

---

## Tools & Technologies Used

* Power BI Desktop
* Microsoft Excel (for dataset)
* DAX (Data Analysis Expressions)
* GitHub (for project submission)
---

## KPI Measures (DAX)

The following measures were created using DAX:

* **Total Sales**

  ```DAX
  Total Sales = SUM('retail_sales_dataset'[Total Amount])
  ```

* **Total Quantity**

  ```DAX
  Total Quantity = SUM('retail_sales_dataset'[Quantity])
  ```

* **Profit (Assumed 20%)**

  ```DAX
  Profit = [Total Sales] * 0.2
  ```

* **Profit Margin %**

  ```DAX
  Profit Margin % = DIVIDE([Profit], [Total Sales], 0)
  ```

---

## Dashboard Features

The dashboard is designed to be clean, interactive, and user-friendly.

### KPI Cards

* Displays Total Sales, Total Quantity, Profit, and Profit Margin
* Provides a quick overview of business performance

### Sales Trend Analysis

* Line chart showing sales over time
* Helps identify growth patterns and seasonal trends

### Category Performance

* Bar chart comparing sales across product categories
* Highlights best and worst performing categories

### Customer Analysis

* Top 10 customers based on total sales
* Helps identify high-value customers

### Gender Analysis

* Compares sales contribution between male and female customers

### Interactive Slicers

* Product Category filter
* Gender filter
* Date range filter
* Enables dynamic data exploration

---

## Key Insights

1. The Clothing category contributes the highest share of total revenue, indicating strong demand in this segment.
2. Sales show variation across different time periods, suggesting possible seasonal trends in customer purchases.
3. Female customers contribute slightly higher overall sales compared to male customers.
4. The Top 10 customers generate a significant portion of total sales, highlighting the importance of customer retention strategies.

---

## Project Files

* `task13_dashboard.pbix` – Power BI dashboard file
* `dashboard_export.pdf` – Exported version of the dashboard
* `insights_task13.txt` – Text file containing key insights
* `retail_sales_dataset.xlsx` – Dataset used for analysis

---

## Conclusion
This project demonstrates the practical application of Business Intelligence concepts, including KPI creation, data visualization, and storytelling.
It highlights how raw data can be transformed into actionable insights to support strategic business decisions.
