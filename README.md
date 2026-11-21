# 📊 Olist E-commerce Data Analysis | Power BI Dashboard

## 📌 Project Overview

This project focuses on analysing Brazilian e-commerce business performance using the **Olist E-commerce Dataset** and Microsoft Power BI.

The main objective is to transform raw e-commerce data into an interactive dashboard that provides insights into sales, customers, products, orders, payments and delivery performance.

The dashboard helps understand business trends, identify performance patterns and support data-driven decision-making.

## 🎯 Project Objectives

- Analyse overall sales and revenue performance.
- Understand customer behaviour and purchasing patterns.
- Identify top-performing products and product categories.
- Monitor order status, cancellations and delivery performance.
- Analyse payment methods and instalment preferences.
- Explore the relationship between product weight, volume and freight charges.
- Identify business insights and opportunities for improvement.

## 📂 Dataset Description

**Dataset:** Olist Brazilian E-commerce Dataset

Olist is a Brazilian online marketplace that connects customers and sellers through an e-commerce platform.

| Dataset Information | Details |
|---|---|
| Total Tables | 9 |
| Total Columns | 49 |
| Total Records | Approximately 200,000 |
| Data Source | Olist E-commerce Dataset |
| Tool Used | Microsoft Power BI |

### Tables Used

1. **Orders dataset** – Order IDs, order status, purchase timestamps and delivery dates.
2. **Order_payments dataset** – Payment type, payment value and instalment information.
3. **Order_reviews dataset** – Review IDs, review scores and customer feedback.
4. **FactSales** – Order items, product IDs, seller IDs, product prices and freight values.
5. **DimProduct** – Product categories, dimensions and product weight.
6. **Customer dataset** – Customer IDs, unique customer IDs, city and state.
7. **Sellers dataset** – Seller IDs, city and state.
8. **Calendar** – Date, year, month and quarter information.
9. **Geolocation dataset** – ZIP codes, latitude, longitude, city and state.

## ⚙️ Methodology

### 1. Data Preparation
- Imported and explored the datasets.
- Checked missing values and data types.
- Removed duplicate records where appropriate.
- Standardised column names and formats.
- Prepared the data for analysis.

### 2. Data Modelling
- Developed a relational data model.
- Created FactSales and dimension tables.
- Established relationships using appropriate key columns.
- Connected the Calendar table for time-based analysis.

### 3. DAX Calculations
Created DAX measures and calculated columns to analyse:
- Total Product Sales
- Total Freight
- Total Orders
- Total Customers
- Average Order Value
- Total Payment Value
- Average Review Score
- Delivery Performance
- Customer Segmentation
- Total Quantity

### 4. Dashboard Development
- Designed interactive report pages.
- Created KPI cards and data visualisations.
- Added slicers and filters.
- Applied consistent formatting and colour themes.
- Developed visuals to support business analysis.

## 📈 Dashboard Pages

The Power BI report contains six analytical pages.

| Page | Description |
|---|---|
| Overview | Overall business performance and key KPIs. |
| Sales Analysis | Sales trends, product category performance and freight analysis. |
| Customer Analysis | Customer distribution, customer segmentation and review analysis. |
| Product Analysis | Product performance, quantity, weight, volume and freight relationships. |
| Order Analysis | Order status, cancellation trends and delivery performance. |
| Payment Analysis | Payment methods, payment value and instalment distribution. |

## 📊 Key Performance Indicators

The dashboard includes important business KPIs such as:

- Total Product Sales
- Total Orders
- Total Customers
- Total Freight
- Average Order Value
- Total Sellers
- Average Review Score
- Total Payment Value
- Cancellation Rate
- Average Delivery Time

### Key Project Figures

| KPI | Reported Value |
|---|---:|
| Total Product Sales | R$ 13,591,643.70 |
| Total Freight | R$ 2,251,909.54 |
| Total Amount (Sales + Freight) | R$ 15,843,553.24 |
| Total Payment Value | R$ 16,008,872.12 |
| Total Orders | 98,666 |
| Delivered Orders | 96,478 |
| Cancelled Orders | 461 |

*Note: These are figures recorded during project analysis. Results may vary depending on report filters and calculation context.*

## 🔍 Key Business Insights

The analysis helps explore several important business patterns:

1. **Sales Performance:** Analyse how sales change over time and how product listings and customer growth relate to sales performance.

2. **Customer Growth:** Understand how the number of unique customers and returning customers contributes to business performance.

3. **Geographical Performance:** Compare sales across states and investigate the relationship between average delivery time and sales.

4. **Product Performance:** Identify top-selling products and categories based on sales and quantity.

5. **Freight Analysis:** Explore how product weight and volume relate to freight charges.

6. **Delivery Performance:** Monitor on-time deliveries, late deliveries and other order statuses.

7. **Payment Analysis:** Understand customer payment preferences and instalment behaviour.

8. **Payment Reconciliation:** Identify the difference between recorded payment value and total product sales plus freight for further investigation.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualisation.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Measures and calculated columns.
- **Data Modelling** – Relationships between fact and dimension tables.
- **Microsoft Excel** – Data inspection and supporting analysis.

## 💡 Conclusion

This project demonstrates how raw e-commerce data can be transformed into meaningful business insights using Power BI.

By combining data preparation, data modelling, DAX calculations and interactive visualisations, the dashboard provides a comprehensive view of sales, customers, products, orders and payment performance.

It also highlights opportunities to improve customer retention, delivery efficiency, product performance and payment monitoring.

---

## 👨‍💻 Author

**Mohammed Shadil P.K.**

Aspiring Data Analyst

**Skills:** Power BI | Data Modelling | DAX | Data Visualization

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback!
