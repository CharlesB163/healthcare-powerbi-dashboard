# Healthcare Claims Power BI Dashboard

## Project Overview
This project showcases an interactive Power BI dashboard analyzing healthcare claims that were scripted and cleaned from healthcare-data-analysis-python

## Tools Used
- Power BI (Dashboard creation, data modeling, slicer)
- PostgreSQL (Data storage and querying)
- Python (Anaconda, Pandas, Jupyter, NumPy, and Matplotlib)
- CSV File

  ## Dashboard Features
  - KPI cards that include total cost, average cost, and total claims
  - Cost analysis by chronic condition
  - Cost comparison by visit type
  - Monthly healthcare spending trends
  - Provider cost analysis
  - High-cost patient identification
  - Interactive Slicer
 
  ## Key Insights
  - Top 20% of patients contribute heavily to healthcare costs
  - ER visits are the highest cost per visit average
  - Chronic conditions like heart disease and diabetes are the main contributors to increased total spending
  - Certain providers cost disproportionately compared to others
  - Healthcare spending is impacted by seasonal trends

   ## Sample Visualization of Database

  ![Cost by Condition](cost_by_chronic_condition_chart.png)

  ## Sample Visualization of Dashboard
  ![Dashboard Screenshot](HealthcareClaimsCostAnalysisDashboard.png)

  ## Interactive Version

 [View Interactive Dashboard on Power BI](https://app.powerbi.com/groups/me/reports/77df9b9b-318d-4032-9d12-d1da1b69b162?ctid=cfa792cf-7768-4341-8857-81754c2afa1f&pbi_source=linkShare)

## How to Run the Project
1. Open the `.pbix` file in Power BI Desktop to view the dashboard interactively.  
2. Ensure that the included CSV files (`patients_clean.csv`, `providers_clean.csv`, `claims_clean.csv`) are in the same folder as the `.pbix` file.  
3. Optionally, Python scripts (`DataScript.ipynb`) can be run to generate or update the CSV files from raw simulated data.  
  
