# Retail Sales Analysis Dashboard

## Project Overview

This project is an interactive **Retail Sales Analysis Dashboard** developed in **Microsoft Power BI**. The report is designed to analyze retail business performance from multiple perspectives, including sales, profit, orders, customers, products, geography, sales channels, and time.

The dashboard converts transactional retail data into an easy-to-understand analytical report that can support business monitoring and data-driven decision-making.

## Project Objectives

The main objectives of this project are to:

- Monitor overall retail sales performance.
- Analyze total profit, profit percentage, quantity, orders, customers, and products.
- Compare performance across regions, cities, product categories, brands, and sales channels.
- Understand how business performance changes over time.
- Compare current performance with previous periods.
- Provide interactive filtering so users can explore the data dynamically.

## Tools & Technologies

- **Microsoft Power BI Desktop** – dashboard development and visualization
- **Power Query** – data preparation and transformation
- **DAX** – measures and business calculations
- **Data Modeling** – relationships between fact and dimension tables
- **Interactive Visualizations** – charts, cards, tables, and slicers

## Data Model

The Power BI report uses a structured retail data model containing the following main tables:

| Table | Purpose |
| --- | --- |
| `Fact Sales` | Stores the main sales transaction measures |
| `Dim Calendar` | Supports year, quarter, month, and time-based analysis |
| `Dim Customer` | Contains customer-related attributes such as city and region |
| `Dim Product` | Contains product information such as product ID, category, and brand |
| `Dim Store` | Contains store/channel-related information |

This structure allows the report to analyze sales measures across different business dimensions.

## Key Measures

The report contains several important measures, including:

- **Total Sales**
- **Total Profit**
- **Total Profit %**
- **Total Orders**
- **Total Customers**
- **Total Products**
- **Total Quantity**
- **Total Sales %**
- **Online Sales**
- **Previous Year**
- **Previous Month Profit**
- **Month-to-Date Profit**
- **Year-to-Date Total**

These measures help evaluate both current business performance and changes over time.

## Dashboard Pages

The Power BI report contains **two main report pages**.

### 1. Overview

The **Overview** page provides a high-level view of retail business performance.

It uses KPI cards, tables, charts, and slicers to help users explore important business metrics.

The analysis includes dimensions such as:

- Region
- City
- Product Category
- Product Brand
- Sales Channel

One of the dashboard visuals specifically analyzes **Total Sales by Region**, making it easier to compare geographical sales performance.

The overview page is useful for quickly understanding the overall condition of the retail business and identifying areas that require deeper analysis.

### 2. Time Series Analysis

The **Time Series Analysis** page focuses on how retail performance changes over time.

The report uses calendar dimensions such as:

- Year
- Quarter
- Month

Time-intelligence measures are also included to support comparisons such as:

- Current vs. previous year
- Previous-month profit
- Month-to-date profit
- Year-to-date performance

Line and column charts make it easier to identify trends, fluctuations, growth patterns, and changes across different periods.

## Interactive Analysis

The dashboard includes interactive slicers and filters that allow users to narrow the analysis.

Users can explore performance based on dimensions such as:

- Year
- Quarter
- Month
- Region
- City
- Category
- Brand
- Channel

When a filter is selected, connected visuals update automatically, allowing users to investigate specific segments without changing the underlying report.

## Business Questions Addressed

This dashboard can help answer questions such as:

1. What is the overall sales performance of the retail business?
2. How much profit is being generated?
3. How many orders, customers, products, and units are involved?
4. Which regions contribute to total sales?
5. How does performance differ by city?
6. Which product categories and brands contribute to performance?
7. How do different sales channels perform?
8. How are sales and profit changing over time?
9. How does current performance compare with previous periods?
10. What are the month-to-date and year-to-date trends?

## Analysis Workflow

The general workflow followed for this project is:

**Data Source → Data Preparation → Data Modeling → DAX Measures → Visualization → Interactive Dashboard → Business Analysis**

### Data Preparation

Data is prepared for reporting using Power BI/Power Query so that it can be used consistently across the dashboard.

### Data Modeling

The sales data is organized around the `Fact Sales` table and supporting dimension tables for calendar, customers, products, and stores.

### DAX Calculations

DAX measures are used to calculate business KPIs and time-based metrics such as total sales, total profit, profit percentage, previous-period values, MTD, and YTD.

### Visualization

The calculated measures are presented using appropriate Power BI visuals such as KPI cards, tables, bar/column charts, pie charts, and line charts.

### Interactivity

Slicers and cross-filtering allow users to explore specific segments and periods dynamically.

## Repository Structure

```text
Retail-Sales-Analysis/
│
├── README.md
├── Retail_Sales.pbix
│
├── Data/
│   ├── Raw_Data/
│   └── Cleaned_Data/
│
├── Dashboard/
│   └── Retail_Sales_Dashboard.png
│
└── Documentation/
```

> The exact repository folders can be adjusted depending on which source datasets, screenshots, and supporting documents are published.

## How to Use the Project

1. Clone or download this GitHub repository.
2. Install **Microsoft Power BI Desktop**.
3. Open `Retail_Sales.pbix`.
4. Navigate between the **Overview** and **Time Series Analysis** pages.
5. Use the available slicers to filter the report.
6. Interact with charts and tables to explore individual segments.
7. Review the KPIs and time-based measures to understand retail performance.

## Skills Demonstrated

This project demonstrates practical skills in:

- Power BI dashboard development
- Data visualization
- Data modeling
- DAX calculations
- Power Query
- KPI development
- Time-series analysis
- Time-intelligence calculations
- Interactive report design
- Retail sales analysis
- Business intelligence

## Future Enhancements

Possible future improvements include:

- Adding sales forecasting.
- Adding drill-through pages for products, customers, and regions.
- Creating additional tooltip pages.
- Adding more period-over-period comparisons.
- Publishing the dashboard to Power BI Service.
- Adding automated data refresh where an appropriate data source is available.
- Expanding the dashboard with customer and product segmentation.

## Project File

The main Power BI report is:

`Retail_Sales.pbix`

## Author

PADIGIREDDY BHANUPRAKASH REDDY 

GMAIL:- bhanuprakashreddy.p1019@gmail.com
linkdin:- https://www.linkedin.com/in/padigireddy-bhanuprakash-reddy-476a32275/?isSelfProfile=true
github:- https://github.com/bhanuprakash1019

B.Tech – Artificial Intelligence  
Aspiring Data Analyst

---

If you find this project useful, feel free to explore the dashboard and repository.
