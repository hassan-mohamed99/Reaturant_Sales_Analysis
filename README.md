# Reaturant_Sales_Analysis
A Power BI project for restaurant sales analysis. It provides insights into total orders, sold items, and income, with breakdowns by category, time, and day of the week to support data-driven decision-making.

# Restaurant Sales Analysis Dashboard

## Overview
This project presents a **Restaurant Sales Analysis Dashboard** built with **Power BI**.  
The goal of this dashboard is to provide insights into restaurant sales performance and order trends.  
It helps management make **data-driven decisions** by monitoring KPIs such as sales, income, and demand by category, time, and day of the week.

---

## 🛠Tools & Technologies
- **Power BI Desktop** for data modeling and visualization.  
- **CSV** as the data source.  
- **DAX (Data Analysis Expressions)** for custom measures and calculations.
- **Figma Tool** for making backgrounds.  

---

**Data Transformation & Cleaning**
   - Handeling missing values.
   - Standardize Data Types.
   - Split Columns if Needed.
   - Create Calculated Columns.
   - Rename Columns for Clarity.

---

**Create Measures**
   - Defined KPIs and calculated measures in Power BI

---

**Using Figma to design custom backgrounds.**

---

## Data Modeling
The data model follows a **Star Schema** design:  
- **Fact Table**  
  - `order.Fact`: contains order details, income, date, and time.  
- **Dimension Tables**  
  - `menu_items.Dim`: categories, item names, prices.  
  - `Date.Dim`: calendar and time intelligence.  
  - `Events.Dim`: special events and dates.  
- **Helper Tables**  
  - `Measures Table`:store measures and calculations.
  - `Measure_Selection`: store and switch measures dynamically.  
  - `Products`: product-level grouping for analysis.  
- **created a Date Dimension table from scratch using Power Query.**
 - This table covers the full date range of the dataset and includes additional columns for detailed analysis.
 - By building this table manually instead of relying only on raw order dates, the model supports Consistent time-based slicers (Year, Month, Week, Day).

---

## Dashboard Preview
![Dashboard Preview](Capture2.PNG)

---

## Key Insights
- **Sold Items, Total Orders, Total Income, Top Category**
  
---

## Features
- Interactive slicers for filtering by **category** and **item**  
- Dynamic slicer between measures (**Income, Items, Orders**)  
- Sales trends by **month, day, and time**  
- Category-level income analysis  
- Orders distribution by year, quarter, month and Day.
- Orders distribution by time of day.  
- Income by category (Asian, American and Italian).  
- Orders by day of the week. 

---


