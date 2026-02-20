<img width="1523" height="254" alt="RetailHeaderImage Feb 19, 2026, 01_09_41 PM" src="https://github.com/user-attachments/assets/2d3cffb9-2ef0-48fb-9821-87642a6ce76c" />

---

# 📊 Retail Execution Performance Dashboard
**Tools Used:**
-Power BI (Version 2025)
-DAX for Calculation
-Sql for data querying

**Overview**

This project simulates a **retail execution analytics dashboard** designed for merchandising and sales operations teams. It tracks **store compliance, stockouts, and product performance** across multiple locations, enabling both high-level KPI monitoring and drill-down analysis at the city and product level.

**Key Features**

* **KPI Cards:**

  * Average Execution Score
  * Sales Velocity
  * On-Shelf Compliance %
  * Planogram Compliance %

* **Interactive Trend & Map Visuals:**

  * Sales Velocity trends over time
  * Sales distribution by Region and City

* **Operational Insights:**

  * Planogram Compliance by City (Bar chart)
  * Drill-through by **City** → view detailed store-level performance, inventory levels, and flagged stockouts

* **Slicers for Interactivity:**

  * Date range, Region, Product Category

**Technical Highlights**

* Built in **Power BI**
* Uses a **star schema** data model with `Fact_Store_Visits`, `Dim_Store`, and `Dim_Product`
* Measures include **On-Shelf Compliance %, Planogram Compliance %, Stockout Rate %, Sales Velocity**, calculated with **DAX**
* Drill-through functionality for operational decision-making

**Insights**
*Analysis shows that West region sales have higher velocity but lower planogram compliance, suggesting operational focus areas


