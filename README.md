# bike-buyers-excel-dashboard

![Excel](https://img.shields.io/badge/Tool-Excel-217346) ![Status](https://img.shields.io/badge/status-complete-brightgreen) 

An end-to-end data analytics project built in Excel, covering the full workflow from raw, messy data to a clean, interactive dashboard. This project demonstrates practical data cleaning, pivot table analysis, and dashboard design skills commonly used in business and data analyst roles.

## Table of Contents

- [Project Overview](#-project-overview)
- [Dataset](#️-dataset)
- [Data Cleaning](#-data-cleaning)
- [Analysis (Pivot Tables & Charts)](#-analysis-pivot-tables--charts)
- [Dashboard Design](#️-dashboard-design)
- [Skills Demonstrated](#️-skills-demonstrated)
- [Files](#-files)
- [How to Use](#️-how-to-use)
- [Preview](#️-preview)
- [Notes](#-notes)
- [License](#-license)

##  Project Overview

The dataset contains customer records related to bike purchases, including demographics (gender, marital status, education, region), income, commute distance, and purchase status. The goal was to clean the raw data, uncover purchasing trends, and present the findings in an interactive, easy-to-navigate dashboard.

##  Dataset

Customer-level records including:

| Field | Description |
|---|---|
| Gender | Customer gender |
| Marital Status | Married / Single |
| Education | Education level |
| Region | Customer's region |
| Income | Customer income |
| Commute Distance | Distance to work/commute |
| Purchased Bike | Whether the customer purchased a bike (Yes/No) |

##  Data Cleaning

- Removed duplicates using Excel's built-in **Remove Duplicates** tool to ensure data integrity.
- Standardized categorical data with **Find & Replace** (`Ctrl+H`) — converting abbreviations like `M`/`S` and `F`/`M` into full, readable labels (`Married`/`Single`, `Female`/`Male`).
- Engineered a new feature — an **Age Brackets** column — using nested `IF` statements to segment customers into age groups (e.g., Adolescent, Middle Age) for more meaningful analysis.

##  Analysis (Pivot Tables & Charts)

- Built pivot tables to calculate **average income by gender and purchase status**, with currency formatting for readability.
- Analyzed the relationship between **commute distance and bike purchases**, including a workaround for correctly sorting non-numeric distance labels (e.g., "10 miles plus").
- Visualized purchasing trends across **custom age brackets** using line charts to reveal which age groups are more likely to purchase.

##  Dashboard Design

- Cleaned up the visual layout by **hiding gridlines** and using **merged cells** for polished section headers.
- Added **interactive slicers** for Marital Status, Region, and Education to let users filter the dashboard dynamically.
- Connected all slicers to multiple pivot tables via **Report Connections**, so a single filter selection updates every chart and table on the dashboard simultaneously.

## Skills Demonstrated

- Data cleaning & standardization
- Feature engineering with nested formulas
- Pivot tables & pivot charts
- Dashboard design and UX
- Interactive filtering with slicers and report connections

## Files

- `bike-buyers-dashboard.xlsx` — the full Excel workbook, including raw data, pivot tables, and the final dashboard.

##  How to Use

1. Download `bike-buyers-dashboard.xlsx` and open it in Excel (2016 or later recommended for full slicer support).
2. Navigate to the **Dashboard** sheet to view the interactive report.
3. Use the slicers (Marital Status, Region, Education) to filter the data — all charts and pivot tables will update automatically.

## Data Source 
https://www.kaggle.com/code/sadiqshah/bike-store-sales-in-europe/data


Feel free to download the workbook and explore the pivot tables and dashboard logic yourself. Contributions and suggestions are welcome!
