
ApexPlanet Task 2

 1. Project Overview 

This repository contains the analysis and business intelligence modeling for the Task 2 internship deliverables at ApexPlanet. The goal was to transform raw sales data into actionable business insights using statistical correlation analysis and structured SQL reporting. 

2. Tech Stack:

Data Wrangling:Python (Pandas) 
Exploratory Data Analysis (EDA): Seaborn, Matplotlib 
Business Intelligence: SQL (DuckDB/SQLite) 

3. Methodology The project followed a three-step data engineering lifecycle: 

a. Cleaning & EDA: Data was processed using Python to identify key revenue drivers, visualized through a correlation heatmap.

 b. Database Modeling: Raw data was ingested into a relational schema (`Sales_Data`) to ensure data integrity and query capability. 

c. Strategic Querying: Complex SQL queries were developed to calculate ROI and revenue-per-customer, providing a foundation for real-time KPI monitoring. ##

 d. Key Insights: 
Marketing Correlation: A strong Pearson correlation (0.99) between Marketing Spend and Revenue validates current marketing strategies. 
ROI Optimization: Electronics and Fashion categories demonstrate the highest efficiency in marketing spend. 
Strategic Recommendation: We recommend reallocating the budget toward these high-ROI segments to maximize top-line growth.

 e. File Structure: 
Task2.ipynb: Python notebook containing the correlation heatmap and EDA. 
Sales_Data_Analytics.csv: The primary dataset.
SQL_Master_Report.sql: The master query used for performance KPI generation.
Project_Report.docx: Detailed business-facing documentation. 


<img width="451" height="625" alt="image" src="https://github.com/user-attachments/assets/94ab7061-670f-4535-be8d-d0e2bf477979" />

