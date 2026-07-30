# 📊 Retail Sales Performance Dashboard
![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoftexcel&logoColor=white)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-blue)
![EDA](https://img.shields.io/badge/EDA-Completed-orange)

## Project Overview

This project analyzes more than 51,000 retail sales records from the Global Superstore dataset using Microsoft Excel.

The objective was to build an interactive executive dashboard that allows users to monitor sales performance, profitability, customer segments, regional results and product-level trends.

### Project Summary

This project demonstrates an end-to-end Excel analytics workflow, including data cleaning, exploratory data analysis, KPI development, interactive dashboard design, and business insight generation using the Global Superstore dataset.

> **Note:** The interactive Excel workbook is available through Google Drive due to GitHub's web upload size limitations. https://drive.google.com/drive/folders/10oo8UEbGPe3ceBRlY-4ohXddtIzH3Yuj?usp=drive_link 

## Dashboard Preview

![Retail Sales Performance Dashboard](https://raw.githubusercontent.com/Smital/Retail-Sales-Performance-Dashboard-/main/images/Retail-Dashboard.png) 

## Business Questions

This project was created to answer the following questions:

- What are the company’s total revenue and profit?
- How do sales change throughout the year?
- Which regions generate the highest sales?
- Which product categories produce the most revenue and profit?
- Which products generate the highest sales?
- Which products are contributing to financial losses?
- Which customer segment generates the most revenue?

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Revenue | $12.64M |
| Total Profit | $1.47M |
| Total Orders | 51,290 |
| Quantity Sold | 178,312 |
| Average Order Value | $246.50 |
| Profit Margin | 11.61% |

## Dashboard Features

- Interactive slicers for Year, Region, Category and Customer Segment
- Monthly sales trend analysis
- Sales performance by region
- Sales and profit analysis by category
- Top 10 products by sales
- Top 10 loss-making products
- Customer segment sales distribution
- Executive-level KPI cards

## Tools and Techniques

| Tool                   | Purpose                     |
| ---------------------- | --------------------------- |
| Microsoft Excel        | Data analysis and dashboard |
| PivotTables            | Data summarization          |
| PivotCharts            | Visualization               |
| Slicers                | Interactive filtering       |
| Conditional Formatting | KPI highlighting            |


## Data Preparation

The dataset was reviewed and prepared before analysis.

Key preparation activities included:

- Preserving the original raw data
- Creating a separate cleaned-data worksheet
- Checking for missing values and duplicates
- Validating sales, profit and date fields
- Retaining legitimate negative-profit transactions
- Creating calculated columns for month, year, quarter and profit margin
- Formatting monetary, date and numerical fields

## Key Insights

### 1. Seasonal sales pattern

Sales were strongest during the final months of the year, with December producing approximately $1.58M in sales. This suggests increased seasonal or holiday demand.

### 2. Technology leads performance

Technology generated approximately $4.74M in revenue and $0.66M in profit, making it the strongest product category.

### 3. Central is the leading region

The Central region produced approximately $2.82M in sales, making it the highest-performing region.

### 4. Furniture has lower profitability

Furniture generated strong revenue but produced substantially less profit than Technology, suggesting lower margins, higher costs or heavier discounting.

### 5. Consumer customers dominate sales

The Consumer segment represented approximately 52% of sales, followed by Corporate and Home Office customers.

### 6. Some products require profitability review

The loss-making product analysis identified products that may require pricing, discount, shipping-cost or supplier-cost review.

## Business Recommendations

- Maintain strong inventory and promotional support for Technology products.
- Prepare additional inventory and marketing campaigns before the fourth-quarter sales peak.
- Study successful sales strategies used in the Central region and assess whether they can be applied elsewhere.
- Review pricing, discount levels and costs for consistently loss-making products.
- Investigate the lower profitability of Furniture despite its strong sales.
- Continue targeting Consumer customers while developing growth opportunities within Corporate and Home Office segments.

## Repository Structure

```text
retail-sales-performance-dashboard/
│
├── README.md
│
├── images/
│   └── retail - dashboard.png
│
└── data/
    └── data-source-information.txt
```

## Dataset

Source: Kaggle
Records analyzed: 51,000+
Dataset type: Retail sales transactions

The original dataset is not included in this repository to respect its applicable licensing and redistribution terms.

## Skills Demonstrated

- Data cleaning and validation
- Exploratory data analysis
- KPI development
- PivotTable and PivotChart analysis
- Interactive dashboard design
- Business performance reporting
- Data visualization
- Business insight generation
- Data storytelling

## Author

- Smital Christian

- Aspiring Data Analyst with experience in UX/UI design, operational support, data validation and customer service.
