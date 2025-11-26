## 🍕 Domino’s Pizza Sales Analysis Dashboard (SQL + Power BI)

**📌 Project Overview**

This project is an end-to-end **Data Analytics and Business Intelligence dashboard** built using **SQL and Microsoft Power BI** to analyze sales performance for a pizza business. The goal of this project is to convert raw transactional data from SQL into meaningful business insights through interactive visualizations.

⚠️ **Disclaimer:**
The data and brand name used in this project are **sample-based and only for learning purposes**. This is not an official project associated with Domino’s or any commercial organization.

**🏢 Business Problem**

The pizza business generates large volumes of sales data daily, making it difficult for business managers to manually track performance, understand customer behavior, and identify revenue-driving products. Without a centralized reporting dashboard, the business lacks:

* Visibility into top and worst-performing pizzas
* Clarity on peak sales days and months
* Insights into category and size-level performance
* Understanding of customer ordering behavior
* A reliable way to make data-driven promotional and inventory decisions

**🎯 Goal of the Dashboard**

The goal of this dashboard is to transform raw sales data into **actionable insights** by providing:
* A single source of truth for sales performance
* Interactive visual analysis for managers and stakeholders
* Quick identification of best and worst sellers
* Clear trends by time, category, and product size
* Decision support for pricing, promotions, and inventory planning

**🎯 Objectives**

* Analyze overall sales performance and customer purchasing patterns
* Identify best-selling and worst-selling products
* Track daily and monthly sales trends
* Understand performance by product category and size
* Build an interactive and user-friendly Power BI dashboard for decision-making

**🧰 Tools & Technologies Used**

**SQL** – Data extraction and querying
**Power BI** – Data modeling and dashboard building
**Power Query** – Data cleaning and transformation
**DAX** – Measures and calculated columns
**Data Modeling** – Relationships between tables
**Power BI Features** – Slicers, navigation buttons, KPI cards, formatting

**🔄 Project Workflow**

**1. Data Collection (SQL)**
* Imported data from SQL databases into Power BI
* Used SQL queries to understand table structure and relationships
* Ensured data accuracy before analytics phase

**2. Data Preparation (Power Query)**
* Removed duplicates and null values
* Standardized column formats (dates, numeric values, text fields)
* Created conditional columns based on business logic
* Optimized data types and naming conventions

**3. Data Modeling**
* Established relationships between tables in Power BI
* Created a star-schema style model for better performance
* Validated relationships and filters across tables

**4.DAX & Calculations**
Created measures for:
* Total Revenue
* Total Orders
* Total Pizzas Sold
* Average Order Value (AOV)
* Average Pizzas per Order
* Category and size-level performance

**📊 Dashboard Walkthrough**

**📄 Page 1 — Top & Bottom Sellers View**
This page focuses on **product performance analysis**.

**Key Visuals:**
**KPI Cards:**
  Displays Total Revenue, Total Orders, Total Pizzas Sold, Average Order Value, and Pizzas per Order.
**Top 5 / Bottom 5 by Revenue:**
  Identifies high-performing and low-performing pizzas by income.
**Top 5 / Bottom 5 by Quantity Sold:**
  Shows demand trends by product popularity.
**Top 5 / Bottom 5 by Orders:**
  Tracks the number of times each pizza is purchased.
**Slicers & Date Filter:**
  Allows filtering by pizza category and date range.

This page enables quick decisions on:

* Which items to promote
* Which items to improve or remove
* Which items generate profit vs volume


**📄 Page 2 — Sales Trends & Category Performance**
This page focuses on **time-based analysis and customer behavior.**

**Key Visuals:**
* **Daily Trend Chart:**
  Highlights which days have higher order volume.
* **Monthly Trend Chart:**
  Identifies seasonal patterns.
* **Category Distribution Chart:**
  Displays sales contribution by pizza type.
* **Size Distribution Chart:**
  Shows customer preference by pizza size.
* **Category Performance Chart:**
  Compares pizzas sold by category.

This page supports:
* Forecasting demand
* Scheduling staff during peak days
* Planning seasonal offers

**📈 Business Impact**

This dashboard helps the business:
* Increase revenue through targeted promotions
* Reduce inventory waste by identifying slow-moving products
* Improve customer experience by optimizing menu strategy
* Allocate resources efficiently during peak hours
* Monitor performance in real time
  
**🔍 Key Business Insights**

* **Classic category** contributes the highest sales and order volume.
* **Large-size pizzas** dominate revenue and demand.
* Sales peak on **Friday and Saturday evenings**.
* **January and July** record the highest order volumes.
* Certain pizzas consistently underperform and may require repricing or redesign.

**🌟 Features**

* Two interactive dashboard pages
* Dynamic date range filters
* Pizza category slicer
* Page navigation buttons
* Drill-down enabled visuals
* Clean and professional formatting
* KPI cards for quick summary
* Category and size-level segmentation

**📈 Learning Outcomes**

* Improved SQL querying skills
* Hands-on DAX implementation
* Practical experience in Power BI dashboard design
* Understanding business requirements from data
* Creating insightful and executive-level reporting

  **Screenshot of dashboard:**
   https://github.com/AHK-999/Domino-s-Pizza-Sales-Dashboard/blob/main/Dashboard%20Image.jpg
