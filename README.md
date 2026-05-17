## Overview

This project focuses on analyzing sales performance data for FNP using Python, SQL, and Excel. The objective of this project is to transform raw sales data into meaningful business insights through data cleaning, exploratory data analysis (EDA), SQL queries, and interactive dashboard visualizations.

The dashboard provides insights into:

* Total Revenue
* Average Delivery Time
* Average Customer Spending
* Total Orders
* Monthly Sales Performance
* Top Products by Revenue
* Sales Performance by Category
* Revenue by Occasions
* Top Cities by Number of Orders

---

## Dataset

The dataset contains sales and customer-related information including:

* Order Details
* Product Information
* Customer Spending
* Delivery Data
* Occasion-based Sales
* City-wise Orders
* Category-wise Revenue

### Sample Columns

* `Order_Date`
* `Delivery_Date`
* `Product_Name`
* `Category`
* `Revenue`
* `Customer_Spending`
* `City`
* `Occasion`

---

## Tools and Technologies Used

| Tool                 | Purpose                        |
| -------------------- | ------------------------------ |
| Python               | Data Cleaning and Analysis     |
| Pandas               | Data Manipulation              |
| NumPy                | Numerical Operations           |
| Matplotlib / Seaborn | Data Visualization             |
| SQL                  | Querying and Business Analysis |
| Excel                | Dashboard and Visualization    |
| Excel / CSV          | Data Storage                   |

---

## Exploratory Data Analysis (EDA)

Performed detailed EDA to analyze:

* Monthly revenue trends
* Customer spending behavior
* Product performance
* Occasion-based sales trends
* Delivery performance
* City-wise order distribution

### EDA Tasks Performed

* Handling missing values
* Removing duplicate records
* Data formatting and transformation
* Statistical analysis
* Trend identification
* Revenue analysis

---

## Data Cleaning

The following preprocessing steps were performed:

* Removed duplicate values
* Handled null or missing data
* Standardized categorical columns
* Corrected inconsistent data types
* Renamed columns for better readability

---

## SQL Analysis

SQL queries were used to generate business insights such as:

* Top-selling products
* Highest revenue categories
* Occasion-based sales analysis
* Customer spending analysis
* City-wise order performance

### Example SQL Query

```sql
SELECT Product_Name, SUM(Revenue) AS Total_Revenue
FROM sales_data
GROUP BY Product_Name
ORDER BY Total_Revenue DESC;
```

---

## Excel Dashboard

An interactive Excel dashboard was created to visualize sales performance and customer behavior.

### Dashboard Features

* KPI Cards for Revenue and Orders
* Monthly Sales Trend Analysis
* Top Products by Revenue
* Category-wise Revenue Analysis
* Occasion-based Revenue Insights
* City-wise Order Analysis
* Interactive Filters and Slicers

---

## Dashboard Insights

Key insights generated from the dashboard:

* Total Revenue reached 3.5M+
* Average Delivery Time is 5.53 days
* Highest revenue generated during Anniversary and Raksha Bandhan occasions
* Sweets category generated the highest sales revenue
* Kavali and Imphal recorded the highest number of orders
* Certain products contributed significantly more revenue compared to others

---

## Project Workflow

```text
Dataset → Data Cleaning → EDA → SQL Analysis → Excel Dashboard → Business Insights
```

---

## Dashboard Preview

Add dashboard screenshots here.

---

## Project Structure

```text
├── Dataset
├── Python Scripts
├── SQL Queries
├── Excel Dashboard
├── Visualizations
└── README.md
```

---

## Conclusion

This project demonstrates practical knowledge of:

* Data Analytics
* SQL Querying
* Data Visualization
* Business Intelligence
* Dashboard Development

The dashboard helps in understanding customer purchasing patterns, revenue trends, and product performance, enabling better business decision-making.

