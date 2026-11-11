# Demand-pulse-demand-inventory-analytics.
Demand & Inventory Intelligence

An interactive Power BI project analysing product demand patterns, warehouse distribution and extreme-demand activity across 50,000 records.

⸻

Project Overview

Demand Pulse is a Power BI analytics project developed to examine product demand patterns, warehouse-level demand distribution and extreme-demand activity across a dataset of 50,000 records.

The project transforms raw demand data into an interactive, five-page report designed to help business stakeholders understand demand behaviour, identify concentration patterns, monitor unusually high-demand events and make more informed demand-planning decisions.

Business Problem

Understanding product demand is essential for effective demand planning and inventory-related decision-making. However, large datasets can make it difficult to identify meaningful patterns, recognise unusual demand activity and understand how demand is distributed across products and warehouse locations.

Without a structured view of demand behaviour, business stakeholders may struggle to identify products with concentrated demand, monitor unusually high-demand events or recognise recurring patterns that deserve further investigation.

This project addresses that analytical challenge by transforming 50,000 demand records into an interactive Power BI report that makes key demand patterns easier to explore and interpret.

The analysis focuses on demand visibility and planning support. It does not directly measure stock availability, stockouts or inventory efficiency because those data points are not included in the dataset.

Project Objectives

The key objectives of Demand Pulse are to:

1. Evaluate overall demand performance: Analyse total demand, order volume, average demand, median demand and demand variability.
2. Identify demand patterns over time: Examine monthly and yearly demand trends.
3. Analyse product-level demand: Identify products contributing the highest demand.
4. Evaluate warehouse demand distribution: Compare demand across warehouse locations and identify areas of relatively high demand concentration.
5. Monitor extreme-demand activity: Examine unusually high-demand records across products, warehouses and time periods.
6. Translate findings into business actions: Present data-informed recommendations to support demand monitoring and inventory-planning discussions.

Dataset Description

The project uses a product demand and inventory dataset containing 50,000 records.

Key fields include:

Field	Description
Category	Product category
Product	Product identifier or name
Warehouse	Warehouse location
Zip	Location postal code
Date	Date associated with the demand record
Time	Time associated with the demand record
Order Demand	Recorded demand quantity
Value	Numeric value supplied in the original dataset

Data Preparation

Data preparation was carried out using Power Query.

Key activities included:

* Reviewing column names and data types.
* Cleaning and standardising date values.
* Creating Year, Month, Month Name and Hour fields.
* Deriving time-of-day categories.
* Classifying demand into Normal, Moderate, High and Extreme categories.
* Preparing the dataset for modelling and reporting.

Tools and Technologies

Tool	Application
Microsoft Power BI	Data modelling, analysis and interactive dashboard development
Power Query	Data cleaning, transformation and preparation
DAX	Creation of analytical measures and KPIs
Microsoft Excel	Source dataset

Dashboard Structure

The report contains five interactive pages:

Page	Focus
01 — Executive Pulse	Overall demand performance and warehouse concentration
02 — Demand Intelligence	Demand distribution, averages, median demand and variability
03 — Product & Warehouse	Product-level demand patterns and warehouse comparisons
04 — Extreme Demand	Unusually high-demand activity across products, warehouses and time
05 — Business Actions	Practical recommendations based on analytical findings

Analytical Approach

The project applies:

* Descriptive analysis.
* Time-based demand analysis.
* Product and warehouse comparisons.
* Demand classification.
* Extreme-demand analysis.
* KPI development and interactive filtering.

Project Limitations

The dataset does not include stock-on-hand quantities, stockout records, supplier lead times, reorder points or inventory holding costs.

Consequently, the report focuses on demand behaviour and planning signals rather than claiming to measure actual inventory performance or prescribe specific stock levels.

The Value field is retained as supplied in the source dataset and is not assumed to represent revenue or profit.

⸻

Project: Demand Pulse — Demand & Inventory Intelligence
Tool: Microsoft Power BI
Dataset: 50,000 records
