## NHS Waiting List Insights – End-to-End Power BI Dashboard

This dashboard provides interactive insights into NHS inpatient and outpatient waiting lists from 2018 to 2021, helping healthcare planners identify bottlenecks, compare service lines, and allocate resources effectively.

#🔍 1. Business Problem

  * The NHS faces growing backlogs in both inpatient and outpatient care. Without a unified dashboard:
  * It’s hard to spot trends over time
  * Comparing wait times across services is difficult
  * Identifying which regions or services are under strain is manual and slow
  * Resource planning is reactive rather than proactive

#📊 2. Dashboard Goal

  * To build a fully interactive Power BI dashboard that helps users:
  * Monitor waiting list trends (2018–2021)
  * Compare inpatient vs outpatient waiting performance
  * Identify which service areas or regions are under pressure
  * Support data-driven decisions on capacity, staffing, and resource distribution

# 📂3. Data Sources

  * NHS public waiting list data in Excel format
  * Inpatient and outpatient datasets with monthly records
  * Geographic / regional data for mapping and comparison

# 🔍4. Process & Methodology

  * Phase	Description
  * Data Collection	Imported multiple Excel files (inpatient & outpatient) via Power BI’s Folder Connector
  * Data Transformation	Used Power Query: cleaning, merging, shaping, handling missing values
  * Data Modeling	Built relationships between fact tables (inpatient & outpatient) and dimension tables (date, region)
  * Measures & Calculations (DAX)	Created KPIs: Total Patients Waiting, Average Waiting Time, % Change YoY
  * Visualization	Designed dashboard with slicers, drill-throughs, KPI cards, maps, comparison charts
    
# 🔑5. Key Features

  * KPI Cards: Show totals for patients waiting, average wait time, and percent change
  * Trend Analysis: Line charts to display backlog evolution over months
  * Service Comparison: Stacked bar or clustered charts comparing inpatient vs outpatient counts
  * Regional View: Map visual showing severity by region
  * Interactive Filters: Slicers for year, month, service type; drill-through for deeper detail
    
# 🖼️ 6. Business Impact & Insights

  * Helps forecast demand surges in certain regions or services
  * Enables performance monitoring of interventions over time
  * Helps prioritize underperforming regions and service lines
  * Improves transparency in reporting to stakeholders

# 7. Tech Stack

  * Power BI Desktop — dashboard creation
  * Power Query — ETL / data prep
  * DAX — calculation of measures and KPIs
  * Excel — raw data source

#8. Screenshots / Dashboard Preview

Here’s a preview of the dashboard layout:
[Screen shoot] : [https://github.com/bhaveshksh/End-End-Power-BI-Dashboard/blob/main/Project%20Screenshot.png]

#9. How to Use / Run

Clone the repository:

git clone [https://github.com/bhaveshksh/End-End-Power-BI-Dashboard.git]

Open the .pbix file in Power BI Desktop
Ensure source data files are available or fix data source paths
Click Refresh to load data
Use slicers, drill-downs, and filters to explore the dashboard


#10. Connect with Me

For questions, feedback, or collaborations:
LinkedIn: [Linkedin.com/in/bhaveshkshirsagar/]
Email: bhaveshkshirsagar50@gmail.com
GitHub Repo: 
