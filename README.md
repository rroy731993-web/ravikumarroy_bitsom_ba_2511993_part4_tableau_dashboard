# ravikumarroy_bitsom_ba_2511993_part4_tableau_dashboard

# Executive Sales Dashboard using Tableau

## Business Problem Summary

The objective of this project is to develop an interactive executive dashboard that enables retail leadership to monitor business performance across sales, profitability, customer segments, regional performance, shipping efficiency, and discount impact. The dashboard supports data-driven decision-making by highlighting business opportunities, operational risks, and key performance indicators.

---

# Dataset Description

The project uses the provided dataset:

**dashboard_sales_data.xlsx**

The dataset contains transactional retail sales data including:

* Order Date
* Region
* State
* Category
* Sub-Category
* Customer Segment
* Sales
* Profit
* Discount
* Shipping Mode
* Delivery Days
* Return Flag
* Order ID

The dataset was imported into Tableau for visualization and dashboard development.

---

# Tableau Workbook Description

The Tableau workbook (**executive_dashboard.twbx**) contains individual worksheets and one executive dashboard designed for business leadership.

The dashboard includes:

* Sales Trend
* Regional Performance
* Category Profitability
* Customer Segment Performance
* Discount vs Profit Analysis
* Shipping Performance
* KPI Summary Cards

---

# Calculated Fields Created

The following calculated fields were created in Tableau:

1. **Profit Margin**

   * Profit / Sales

2. **Cost**

   * Sales − Profit

3. **Average Order Value**

   * Sales / COUNTD(Order ID)

4. **Return Rate**

   * Returned Orders / Total Orders

5. **Shipping Delay Bucket**

   * Fast (0–2 Days)
   * Normal (3–5 Days)
   * Delayed (6+ Days)

---

# Dashboard Components

The executive dashboard contains:

* Sales Trend Line Chart
* Regional Performance Bar Chart
* Category Profitability Bar Chart
* Customer Segment Performance Bar Chart
* Discount vs Profit Scatter Plot
* Shipping Performance Bar Chart
* KPI Cards:

  * Total Sales
  * Total Profit
  * Profit Margin

---

# Filters and Interactions Used

Interactive filters included:

* Region
* Category
* Customer Segment
* Date
* Ship Mode

Dashboard actions allow users to filter all visualizations by selecting values from charts and filters.

---

# Key Business Insights

Major findings include:

* South generated the highest total sales (**$64.69M**).
* Technology is the highest profit-generating category (**$28.04M**).
* Copiers are the most profitable sub-category (**$7.31M**).
* Home Office customers generated the highest sales (**$74.50M**).
* Higher discount levels generally reduce profitability.
* Shipping performance varies across shipping modes, indicating opportunities for logistics optimization.

---

# Dashboard Story Summary

The dashboard provides leadership with a complete view of sales performance, regional contribution, customer behaviour, product profitability, discount effectiveness, and shipping performance. It identifies high-performing business areas while highlighting operational improvement opportunities to support strategic decision-making.

---

# Assumptions and Limitations

## Assumptions

* The provided dataset is complete and accurate.
* All sales and profit values are recorded correctly.
* Delivery Days accurately represent shipping performance.

## Limitations

* Historical data only; no predictive analytics.
* External market conditions are not considered.
* Customer lifetime value and demand forecasting are outside the project scope.

---


**Student ID:** bitsom_ba_2511993
