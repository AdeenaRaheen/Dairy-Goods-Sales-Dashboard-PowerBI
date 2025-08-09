# Dairy Sales Performance Dashboard

## Project Overview

This repository hosts a comprehensive Power BI dashboard designed to provide key insights into dairy sales performance, operational efficiency, and product quality from 2019 to 2022. The dashboard enables stakeholders to monitor critical metrics, identify trends, and make data-driven decisions related to sales, inventory, and product management.

## Features

The dashboard is structured into two main pages, each focusing on different aspects of the dairy business:

### 1. Overview & Sales Performance

This page provides a high-level summary of the overall business health and key sales trends.

* **Key Performance Indicators (KPIs):**
    * Total Revenue (INR)
    * Total Quantity Sold
    * Current Stock Value (INR)
    * Total Cow Population
    * Total Land Area (Acres)
* **Visualizations:**
    * **Total Revenue by Location (Matrix):** Breaks down revenue contributions across different geographic locations.
    * **Total Revenue by Brand (Clustered Column Chart):** Shows revenue performance for each dairy brand.
    * **Total Quantity Sold by Product (Clustered Bar Chart):** Highlights top-selling products by quantity.
* **Interactive Slicers:**
    * Filter by Date (Year, Quarter, Month hierarchy)
    * Filter by Brand

**Overview & Sales Performance Page:**
*[[Overview Page Screenshot]][(<img width="896" height="507" alt="Dairy Sales performance overview" src="https://github.com/user-attachments/assets/b60d3b30-055b-44de-99d3-f938aa1544f0" />)]

## 2. Operations & Product Quality

This page delves into more detailed operational metrics, including sales distribution channels, inventory levels, and product quality insights.

* **Visualizations:**
    * **Total Quantity Sold by Customer Location and Sales Channel (Stacked Column Chart):** Analyzes sales distribution patterns.
    * **Average Shelf Life by Storage Condition (Clustered Column Chart):** Provides insights into the impact of storage on product quality.
    * **Products by Average Shelf Life (Table):** Detailed breakdown of average shelf life for individual products, sortable for quick analysis.
    * **Inventory Stock Levels & Reorder Info (Table):** Tracks current stock, minimum thresholds, and reorder quantities for effective inventory management.
* **Interactive Slicers:**
    * Filter by Location
    * Filter by Sales Channel

**Operations & Product Quality Page:**
<img width="896" height="507" alt="Dairy-Goods-Sales-Dashboard-PowerBI" src="https://github.com/user-attachments/assets/c2fe5ffc-1c86-42c3-befa-bd391c98dde4" />


## Data Source

The dashboard utilizes a simulated dataset containing dairy sales records, product information, customer locations, inventory levels, and farm-related metrics.

## How to View/Use
1.  Download the `.pbix` file from this repository.
2.  Open the file using Power BI Desktop.
3.  **Explore the Dashboard:**
    * Use the navigation tabs at the bottom to switch between the "Overview & Sales Performance" and "Operations & Product Quality" pages.
    * Utilize the slicers on the left-hand side of each page to filter data by Date, Brand, Location, and Sales Channel. Note that key filters are synchronized across pages for a seamless experience.
    * Hover over visuals for detailed tooltips.
    * Click on elements within charts (e.g., a specific brand bar, a location in the matrix) to cross-filter other visuals on the same page.

## Technologies Used

* **Microsoft Power BI Desktop:** For data modeling, visualization, and dashboard creation.
* **DAX (Data Analysis Expressions):** For creating custom measures and calculated columns.

## Author:** Adeena Raheen
