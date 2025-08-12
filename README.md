#Project: NHS Waiting List Insights – End-to-End Power BI Dashboard

#1. Business Problem:-
The NHS has been experiencing increasing patient backlogs in both inpatient and outpatient services. Without a consolidated view of the data, it’s challenging for management to monitor trends, identify bottlenecks, and make timely resource allocation decisions.

#2. Goal of the Dashboard:-
To develop a fully interactive Power BI dashboard that enables:
Monitoring of waiting list trends from 2018–2021.
Comparison between inpatient and outpatient waiting times.
Identification of service areas under pressure.
Data-driven decision-making for resource planning.

#3. Data Sources:-
NHS Public Waiting List Data (Excel format).
Inpatient and outpatient datasets covering monthly trends.
Geographic data for regional analysis.

#4. Process & Methodology:-
Data Collection: Imported multiple Excel files (inpatient & outpatient) via Power BI’s folder connector.
Data Transformation: Used Power Query for cleaning, merging, and shaping the datasets.
Data Modeling: Created relationships between fact tables (inpatient, outpatient) and dimension tables (date, region).
Measures & Calculations: Wrote DAX formulas for KPIs such as Total Patients Waiting, Average Waiting Time, and % Change vs Previous Year.
Visualization: Designed an intuitive, interactive report with slicers, drill-throughs, and KPI cards.

#5. Key Features of the Dashboard:- 
KPI Cards: Display total patients waiting, average waiting times, and year-on-year changes.
Trend Analysis: Line chart tracking monthly backlog trends.
Service Comparison: Stacked bar charts for inpatient vs outpatient counts.
Regional View: Map visualization showing backlog severity by location.
Interactive Filters: Year, month, and service type slicers for targeted analysis.

#6. Business Impact & Insights:-
Capacity Planning: Forecasts demand surges for hospitals.
Performance Tracking: Monitors effectiveness of intervention strategies.
Strategic Decision-Making: Helps identify underperforming regions and prioritize improvements.
Transparency: Enables clear communication of healthcare performance to stakeholders.

#7. Tech Stack:- 
Power BI Desktop – Dashboard creation.
Power Query – Data preparation and transformation.
DAX – Calculated measures and KPIs.
Excel – Source data format.

#8. Screenshots / Demos:-
Show what the dashboard lool like. - ![Alt text](https://github.com/bhaveshksh/End-End-Power-BI-Dashboard/blob/main/Project%20Screenshot.png)
