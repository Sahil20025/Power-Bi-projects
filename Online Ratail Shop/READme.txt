# Power BI Report

## Overview

This repository contains a Power BI report titled `report.pbix`. The report is designed to provide insights into revenue data for the year 2011 and includes analysis on top-performing countries, excluding the United Kingdom.

## Contents

- `report.pbix`: The Power BI report file.
- `README.md`: This file, providing an overview and explanation of the report contents.

## Report Structure

The report is structured to address two key questions:
1. **Time Series of Revenue Data for 2011**: This analysis provides a month-by-month breakdown of revenue for the year 2011, allowing for the identification of seasonal trends and deeper insights into revenue fluctuations.
2. **Top 10 Countries by Revenue (Excluding UK)**: This analysis highlights the top 10 countries generating the highest revenue, along with the quantity sold. The analysis explicitly excludes the United Kingdom from the visualizations.

## Data Model

The data model includes the following components:
- **Tables**: Various tables containing revenue, country, and date information.
- **Relationships**: Relationships between tables to support accurate data aggregation and filtering.
- **Measures**: DAX measures used to calculate total revenue, total quantity sold, and other key metrics.

## Visualizations

The report includes the following visualizations:

### 1. Time Series of Revenue Data for 2011
- **Line Chart**: This chart visualizes the total revenue for each month in 2011, allowing for the identification of seasonal trends and patterns.
  - **X-Axis**: Month
  - **Y-Axis**: Total Revenue

### 2. Top 10 Countries by Revenue (Excluding UK)
- **Bar Chart**: This chart displays the top 10 countries by total revenue, excluding the United Kingdom, along with the quantity sold.
  - **X-Axis**: Country
  - **Y-Axis**: Total Revenue
  - **Tooltip/Values**: Quantity Sold

## Instructions

To view and interact with the report:
1. Download the 'report.pbix' file.
2. Open the file using Microsoft Power BI Desktop.
3. Explore the visualizations and data insights provided within the report.

