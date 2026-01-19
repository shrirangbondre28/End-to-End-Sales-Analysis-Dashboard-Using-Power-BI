## 🚴Power BI-Sales-Analysis-Dashboard
In this project, we perform sales data analysis to track business performance across revenue, profit, orders, customers, and returns using Power BI.
## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Source](#data-source)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Data Modeling](#data-modeling)
- [Live Dashboard](#live-dashboard)
- [Inferences](#inferences)
- [Recommendations](#recommendations)

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

## 
