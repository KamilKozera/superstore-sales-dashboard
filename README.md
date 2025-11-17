# Superstore - Sales Performance Dashboard

This repository contains a comprehensive sales performance dashboard for "Real Canadian Superstore", developed using Power BI. The primary objective of this dashboard is to provide key stakeholders with actionable insights into sales trends, profitability, and regional performance.

## Dashboard Demonstration

The following GIF showcases the dashboard's key features and interactivity, allowing users to dynamically filter and analyze the data.

![Dashboard Demo](PBIDesktop_RCbkz8DDDiv.gif)

## Project Overview

This interactive dashboard provides a high-level overview of sales activities for the selected year. It answers critical business questions such as:
*   What are the total sales and profit?
*   How is the business growing compared to the previous year?
*   Which states and regions are the top contributors to sales?
*   What are the monthly sales trends and are there any seasonal patterns?

## Key Features & Insights

*   **At-a-Glance KPIs:** The dashboard prominently displays key performance indicators:
    *   **Total Sales:** \$2.3M
    *   **Total Profit:** \$286.4K
    *   **Sales Year-over-Year Growth:** 20.36%
    *   **Profit Year-over-Year Growth:** 14.24%

*   **Geographical Performance Analysis:**
    *   **Sales by State:** A horizontal bar chart clearly identifies California as the top-performing state.
    *   **Sales by Region:** A donut chart breaks down sales contributions, with the West region leading at 30.77%.

*   **Time-Series Analysis:**
    *   The "Total Sales by Month" column chart reveals sales trends throughout the year, highlighting peak months like December and September.

*   **Interactive Filtering:**
    *   The dashboard is fully interactive, featuring slicers for **Segment**, **Category**, and **Year**. These allow for a granular analysis of the data, empowering users to drill down into specific business areas.

## Technical Skills & Tools Used

*   **Tool:** Microsoft Power BI
*   **Data Modeling:** Established relationships between data tables to create a robust and scalable data model.
*   **DAX (Data Analysis Expressions):**
    *   Developed custom DAX measures from scratch to calculate all key metrics.
    *   Implemented advanced time-intelligence functions (`TOTALYTD`, `DATEADD`, `SAMEPERIODLASTYEAR`) to compute critical Year-over-Year (YoY) growth metrics for both sales and profit.
*   **Data Visualization:**
    *   Utilized a combination of bar charts, column charts, KPI cards, and a donut chart to present data in an intuitive and easily digestible format.
    *   Focused on a clean and professional UI/UX design to ensure clarity and ease of use.

## Project Files

*   `superstore.pbix`: The Power BI project file containing the full solution - data model, Power Query transformations, DAX measures, and the report layout.
*   `PBIDesktop_RCbkz8DDDiv.gif`: A short animation showcasing the dashboard's features.
*   `README.md`: This project description file.
