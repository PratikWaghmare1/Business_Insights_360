# Business_Insights_360

## Project Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

I worked on this project by following the Codebasics PowerBi Course, Link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYzcxOTU3NjMtN2YwNy00ZWNmLTk4Y2YtNGUyMGJjNzcyNTM5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech stacks

- SQL
- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

## PowerBI techniques Learnt

- What are all the questions should be asked before staring the project
- Creating calculated columns
- creating measure using DAX language
- Data modeling
- Using Bookmarks to switch between two visuals
- Page navigation with buttons
- Using divide function to prevent zero division errors
- creating date table using m language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- PowerBi services
- Publishing reports to PowerBi services
- Setting up personal gateway to set up the auto refresh of data
- PowerBi App creation
- Collaboration, workspace, access permissions in PowerBi services

## Business related terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Company’s back ground

AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors

Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry. 

Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project

### Dataset **Understanding.**

Before diving into analysis, it’s crucial to thoroughly understand the dataset.

- Dimension Table: Contains static data, such as customer and product details.
- Fact Table: Contains transaction data.
Example Dataset
- gdb041:

  - dim_customer: 27 distinct markets, 75 customers, 2 sales platforms (Brick & Mortar, E-commerce)
  - dim_market: 27 markets across 4 regions (APAC, EU, North America, LATAM)
  - dim_product: Covers various divisions (e.g., Peripherals, Accessories) and categories (e.g., Internal HDD, Keyboards)
- Fact Tables:

  - fact_forecast_monthly: Contains forecasted quantities for customer needs, aiding in warehouse cost reduction and higher satisfaction.
  - fact_sales_monthly: Similar structure to forecast table but contains actual sales data.

## Data Importation in Power BI

- As the data is stored in a MySQL database, I imported it into Power BI by connecting with the appropriate database credentials.

## Data Model

- Data modeling is the foundation of any report, directly influencing performance. Following best practices is crucial for building an efficient model.
- In this project, I applied the Snowflake schema for data modeling. Learn more about data modeling best practices here. [Blog](https://addendanalytics.com/blog/data-modelling-best-practices/)

![Screenshot 2024-08-15 110644](https://github.com/user-attachments/assets/876bd4e9-1500-48d3-a121-2191d3cf4b34)

### Dashboard Design

Based on stakeholder requirements and mockups, the team designed and developed various dashboard views.

## Home view

The Home view provides easy navigation to the following pages:

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Products
- Support

## Overall Report

[![Overall Report.gif](https://github.com/Naveen-S6/Business_Insights_360/blob/main/Resources/Overall.gif)](https://github.com/user-attachments/assets/f5b424f0-03d5-4bc5-99e9-305ebc6fa38e
)

## Info Page

![Screenshot 2024-08-15 114421](https://github.com/user-attachments/assets/35f2b96b-0ef1-409f-8a2d-56ee91b58c80)

## Finance View

![Screenshot 2024-08-15 114155](https://github.com/user-attachments/assets/b9e5e696-d37e-41a4-ba60-ab2307668b78)
## Sales View

![Screenshot 2024-08-15 114700](https://github.com/user-attachments/assets/ce2e786a-6bc2-4ad4-979e-64c7bda0c2a3)

## Marketing View

![Screenshot 2024-08-15 113719](https://github.com/user-attachments/assets/86dace17-28a2-43b9-a611-c4092a4022e8)

## Supply chain View

![Screenshot 2024-08-15 113411](https://github.com/user-attachments/assets/fb70e3bd-e571-40a7-b0bc-0b94a2983470)

## Executive View

![Screenshot 2024-08-15 113224](https://github.com/user-attachments/assets/6874883a-4e2c-4c37-9d73-9dc7e2b0c235)

You can find the full report file  : (https://app.powerbi.com/view?r=eyJrIjoiYzcxOTU3NjMtN2YwNy00ZWNmLTk4Y2YtNGUyMGJjNzcyNTM5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Project Outcome

This report empowers stakeholders to make informed, data-driven decisions. It provides actionable insights that address various business scenarios, helping answer critical "why" questions effectively.

