# Zepto Sales Analysis Dashboard

## Project Overview

This project analyzes a 1,500-order Zepto-style retail sales dataset using Microsoft Excel. The objective is to understand sales performance, customer behavior, payment preferences, product/category performance, delivery efficiency, and profitability through pivot-table analysis and an interactive dashboard.

The project is designed as a portfolio-ready **Data Analytics / Excel Dashboard** project for GitHub.

## Business Objective

The main business goal is to identify the factors driving revenue and profit while understanding customer segments, purchasing patterns, payment methods, delivery performance, and city/category-level performance.

### Key Business Questions

- How much revenue and profit are being generated?
- Which customer types contribute the most sales?
- Which cities and categories perform best?
- Which payment methods are most commonly used?
- What is the average order value?
- How efficient is delivery?
- Which areas have stronger or weaker profitability?
- Where are opportunities to improve sales and margins?

## Dataset Information

- **Records:** 1,500 orders
- **Columns:** 22
- **Year:** 2025
- **Cities:** Bangalore, Delhi, Mumbai
- **Customer Types:** Bulk, New, Returning
- **Payment Methods:** UPI, Netbanking, GPay, Card, Wallet, PhonePe, COD
- **Main Categories:** Beverages, Frozen, Veg, Snacks, Fruits, Dairy, Essentials, Other, Baby, Bakery

### Important Columns

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of the order |
| Customer_Name | Customer identifier |
| Customer_Type | New, Returning, or Bulk customer |
| Customer_Segment | Business/customer segment |
| City | Order location |
| Payment_Method | Payment method used |
| Product_Name | Product identifier/name |
| Category | Product category |
| Qty | Quantity ordered |
| Price | Product price |
| Discount | Discount applied |
| Subtotal | Order value after discount |
| Tax | Tax amount |
| Delivery_Fee | Delivery charge |
| Surge_Fee | Surge charge |
| Total | Final order value |
| Delivery_Time | Delivery time in minutes |
| Profit | Profit generated from the order |

## Tools Used

- **Microsoft Excel**
  - Data cleaning
  - Data formatting
  - Calculated fields/formulas
  - Pivot Tables
  - Pivot Charts
  - Dashboard creation
- **GitHub**
  - Project documentation
  - Portfolio presentation
  - Version control

## Data Cleaning

The dataset was prepared for analysis by:

1. Checking column names and data types.
2. Formatting order dates correctly.
3. Checking for missing or inconsistent values.
4. Verifying numeric fields such as quantity, price, discount, tax, total, and profit.
5. Checking calculated sales and profit values.
6. Organizing categorical fields for pivot-table analysis.
7. Creating summary views using Pivot Tables.

## Dashboard KPIs

The dashboard focuses on the following high-level KPIs:

- **Total Sales:** ₹563,992.25
- **Total Orders:** 1,500
- **Total Quantity Sold:** 4,207
- **Average Order Value:** ₹375.99
- **Total Profit:** ₹49,074.35
- **Average Delivery Time:** 24.71 minutes
- **Profit Margin:** approximately 8.70%

## Dashboard Features

The Excel dashboard is intended to provide a single-page management view containing:

### KPI Cards
- Total Sales
- Total Orders
- Total Profit
- Average Order Value
- Average Delivery Time

### Recommended Visuals

- Monthly Sales Trend
- Sales by City
- Sales by Customer Type
- Sales by Customer Segment
- Sales by Product Category
- Payment Method Analysis
- Profit by Category
- Delivery Time Analysis

### Filters / Slicers

Where supported by the Excel dashboard:

- Year
- Month
- City
- Customer Type
- Customer Segment
- Payment Method
- Category

## Key Findings

### 1. Customer Type

Bulk customers are the dominant revenue contributor, generating approximately **₹470K** in sales from 1,247 orders. New and returning customers contribute significantly less revenue in this dataset.

### 2. City Performance

**Bangalore** is the strongest city by sales, generating approximately **₹201.9K**, followed by Delhi at approximately **₹180.6K** and Mumbai at approximately **₹169.4K**.

### 3. Payment Method

**UPI** is the leading payment method, accounting for approximately **₹188.8K** in sales and 493 orders.

### 4. Category Performance

**Beverages** is the highest-sales category at approximately **₹82.6K**, followed by Frozen at approximately **₹76.0K**.

### 5. Profitability

The dataset generates approximately **₹49.1K profit**, with an overall profit margin of about **8.7%**.

### 6. Delivery Performance

Average delivery time is approximately **24.7 minutes**, providing a useful operational KPI for evaluating delivery efficiency.

## Business Recommendations

1. **Focus on Bulk Customers**
   - Bulk customers are responsible for most of the revenue.
   - Develop retention and volume-based offers for this segment.

2. **Strengthen Bangalore Performance**
   - Bangalore is the highest-performing city.
   - Identify the products and customer segments driving this performance and replicate successful strategies elsewhere.

3. **Promote High-Performing Categories**
   - Beverages and Frozen products generate strong sales.
   - Use bundles and cross-selling to increase order value.

4. **Optimize Payment Experience**
   - UPI is the leading payment method.
   - Ensure fast, reliable digital-payment processing and consider targeted offers where appropriate.

5. **Monitor Profit, Not Only Revenue**
   - High sales do not automatically mean high profitability.
   - Track profit and profit margin by city, category, customer type, and product.

6. **Improve Delivery Efficiency**
   - Monitor delivery time alongside sales and customer segments.
   - Investigate locations or periods with unusually high delivery times.

## Project Structure

```text
Zepto-Sales-Analysis/
│
├── Dataset/
│   └── zepto_sales_data.xlsx
│
├── Dashboard/
│   └── zepto_sales_dashboard.xlsx
│
├── Documentation/
│   └── README.md
│
└── Screenshots/
    └── dashboard.png
```

## Excel Workbook Structure

The workbook contains:

- **Sheet1** – Raw/analysis dataset
- **Pivot** – Pivot-table based analysis
- **Dash** – Dashboard sheet

## Project Outcome

This project demonstrates practical Excel data-analytics skills including data preparation, KPI calculation, Pivot Tables, business analysis, visualization, and dashboard development.

The final dashboard converts raw transactional data into business insights that can support decisions related to customers, products, cities, payments, delivery operations, sales, and profitability.

## Skills Demonstrated

**Excel | Data Cleaning | Data Analysis | Pivot Tables | Pivot Charts | KPI Design | Dashboard Development | Business Intelligence | Data Visualization | Business Insights**

## Author

**Sanjai**

BCA / Data Analytics Student

## License

This project is created for educational, portfolio, and demonstration purposes.
