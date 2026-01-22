## 🚴Power BI-Sales-Analysis-Dashboard
In this project, we perform sales data analysis to track business performance across revenue, profit, orders, customers, and returns using Power BI.
## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Source](#data-source)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Data Modeling](#data-modeling)
- [Dashboard Pages & Features](#dashboard-pages--features)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Tools & Technologies](#tools--technologies)

## Project Overview
This project focuses on building an end-to-end Sales Analysis Dashboard using Power BI, aimed at tracking business performance across revenue, profit, orders, customers, products, and returns.
The dashboard is fully dynamic and interactive, enabling users to analyze trends over time, compare performance against targets, drill down into product and customer details, and identify key drivers of profitability and returns.

The project demonstrates real-world Power BI skills, including data modeling, Power Query transformations, advanced DAX measures, and interactive reporting using slicers, parameters, and bookmarks.

## Problem Statement 
Sales teams and decision-makers often struggle to answer questions like:

- How is revenue and profit trending over time?

- Which product categories and products drive the most orders and returns?

- Are monthly sales, profit, and orders meeting targets?

- Which customers contribute the highest revenue?

- How do returns impact overall profitability?

This project addresses these questions by converting raw transactional data into actionable insights through a centralized Power BI dashboard.

## Data Source
The dataset consists of structured sales and returns data, including:

- Sales transactions (orders, quantities, revenue, cost, profit)

- Returns data (returned quantities, return rate)

- Customer attributes (income level, occupation, geography)

- Product hierarchy (category, subcategory, product details)

- Calendar table for time-based analysis

- Territory data for geographic insights

## Data Cleaning & Preparation
Data preparation was performed using Power Query, including:

- Promoting headers and correcting data types

- Currency formatting for revenue and profit fields

- Removing irrelevant and redundant columns

- Renaming columns for clarity and consistency

- Filtering invalid or incomplete records

- Creating derived columns using text and mathematical transformations

- Ensuring clean keys for relationships across tables

These steps ensured the dataset was analysis-ready and optimized for performance.

## Data Modeling
Implemented a star schema data model

- Fact tables:

       Sales Data

       Returns Data

- Dimension tables:

      Calendar Lookup

      Customer Lookup

      Product Lookup

      Product Category & Subcategory Lookups

      Territory Lookup

- One-to-many relationships with proper filter direction

- Separate Measure Table created to organize all DAX measures

## Dashboard Pages & Features
1️⃣ Executive Dashboard

- KPIs:

       Total Revenue

       Total Profit

       Total Orders

       Return Rate

- Revenue trend analysis with time intelligence

- Orders by product category

- Top products by orders, revenue, and return percentage

- Monthly performance vs targets (Orders, Revenue, Profit)
  
- Most ordered and most returned product types

- Custom navigation panel and clear-filters functionality using bookmarks

2️⃣ Geographic Analysis (Map Page)

 - Customer distribution across continents

 - Geographic contribution to sales and customers

 - Interactive map visuals for regional insights


3️⃣ Product Detail Analysis

 - Product-level drill-down

 - Monthly Orders vs Target (Gauge)

 - Monthly Profit vs Target (Gauge)

 - Profit trend analysis

 - Return % trend over time

 - Dynamic What-If parameter for price adjustment

 - Metric selector (Orders, Profit, Revenue, Returns, Return %)

This page enables scenario analysis and product performance evaluation.

4️⃣Customer Detail Analysis

 - Total customers and average revenue per customer

 - Customer growth trend over time

 - Orders segmented by income level and occupation

 - Top 100 customers by revenue

 - Identification of top customer by revenue

 - Year-based filtering for comparative analysis

## Insights 

 - Revenue and profit show a strong upward trend over time, with seasonal fluctuations

 - Accessories and bikes contribute the highest order volumes

 - Certain high-selling products also exhibit higher return rates, impacting net profit

 - Customer growth accelerates significantly after mid-2021

 - A small subset of customers contributes disproportionately to total revenue

 - Monthly performance frequently misses targets, highlighting optimization opportunities

## Recommendations
 - Focus on reducing return rates for high-volume products to protect margins

 - Prioritize high-value customers through targeted retention strategies

 - Use price-adjustment scenarios to evaluate profitability before implementing pricing changes
   
 - Improve forecasting accuracy by leveraging historical trends and seasonality

 - Monitor category-level performance regularly to optimize inventory and promotions

## Tools & Technologies

    - Power BI

    - Power Query

    - DAX

   -  Star Schema Data Modeling

   -  Interactive Dashboards & Bookmarks




