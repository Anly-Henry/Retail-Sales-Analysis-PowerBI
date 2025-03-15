# Maven Market Power BI Project

## About the Project

Maven Market Sales Analysis Dashboard is an end-to-end Power BI project developed using real-world datasets provided by Maven Analytics. The goal of this project is to analyze retail transactions across multiple regions, product categories, and customer segments, and to deliver a dynamic, interactive dashboard for business stakeholders.

The dashboard highlights key performance indicators such as current month transactions, profit, return rate, revenue vs target, weekly revenue trends, and brand-level performance metrics. This project demonstrates my ability to work with raw datasets, perform data modeling, and create visually compelling dashboards that support data-driven decision-making.

## Table of Contents
 
- [Project Objective](#project-objective)  
- [Dataset Overview](#dataset-overview)  
- [Power BI Dashboard Features](#power-bi-dashboard-features)  
- [Strategy and Approach](#strategy-and-approach)  
- [Challenges Faced](#challenges-faced)  
- [Key Insights and Outcomes](#key-insights-and-outcomes)  
- [Key Learnings](#key-learnings)  
- [Dashboard Screenshot](#dashboard-screenshot)  
- [Contact](#contact)

## Project Objective

- Visualize current month’s KPIs like Transactions, Profit, and Returns
- Highlight regional performance through a map and tree map
- Track brand-level profit, profit margin, and return rate
- Compare actual revenue vs target revenue
- Spot weekly revenue trends over the year

## Dataset Overview

The project uses the following CSV datasets provided by Maven Analytics:

- Calendar.csv – Contains date-related fields
- Customers.csv – Customer demographic and location info
- Products.csv – Product names, categories, and prices
- Regions.csv – Mapping of countries to regions
- Returns_1997-1998.csv – Returned orders and quantities
- Stores.csv – Store name and location
- Transactions.csv – Sales transaction records

## Power BI Dashboard Features

- KPI Cards for monthly transactions, profit, and returns with goal comparison
- Weekly revenue trend chart
- Map visual to explore transactions by store city
- Treemap to analyze transactions by country, state, and city hierarchy
- Matrix visual to compare brands by transactions, profit margin, and return rate
- Gauge chart to show actual revenue vs. target
- Country-level slicer with "Select All" option for interactivity

## Strategy and Approach

1. **Data Preparation and Modeling**
  - Cleaned and structured data using Power Query
  - Established relationships across multiple tables
  - Created a calendar table for time-based analysis and marked it as a date table

2. **Calculated Columns and DAX Measures**
 - Built measures for KPIs, profit margins, return rates, and target comparisons
 - Developed time intelligence logic for current and previous months

3. **Visual Design and Formatting**
 - Used a consistent dark theme with accessible, muted color palettes
 - Applied conditional formatting in matrix and KPI cards
 - Configured slicers, tooltips, and shadow effects for visual polish

## Challenges Faced

| Challenge | Solution |
|----------|----------|
| Auto-generated date hierarchies cluttering visuals | Used raw date fields instead of hierarchy |
| Connecting returns with transactions | Applied related functions to bridge data |
| Formatting text inside data bars for readability | Manually changed font color to improve visibility against the data bar background

## Key Insights and Outcomes

- The USA leads in both transactions and profit, followed by Mexico and Canada
- Some brands with high profit margins also had higher return rates, indicating potential quality issues
- Weekly revenue trends suggest seasonal spikes which could guide promotional timing
- Dashboard enables data slicing and comparison with dynamic user interaction

## Key Learnings

- Built confidence in using DAX for real-world KPI calculations and targets
- Learned how to structure a professional data model for performance
- Gained hands-on experience in creating a high-impact visual story through Power BI
- Developed a better understanding of data storytelling through filters and visuals

## Dashboard Screenshot

![MavenMarket sales Report](https://github.com/user-attachments/assets/6819af2c-b2eb-4ae4-9b5e-d5e440f18222)

## Contact

If you’d like to connect:

- LinkedIn: https://www.linkedin.com/in/anlyhenry/
- Email: [anly.henry20@gmail.com]


