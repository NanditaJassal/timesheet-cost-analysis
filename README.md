# timesheet-cost-analysis
Python project for timesheet analysis, labour cost estimation, and data visualisation.

Project Overview

This project analyses employee timesheet records using Python to understand working hours, department utilisation, and estimated labour costs. It transforms raw timesheet data into meaningful summaries and visualisations to support workforce and cost analysis.

Objectives

Analyse employee working hours and contracted hours.
Compare working hours across departments.
Estimate labour costs using hourly rates.
Identify weekly trends in hours and labour costs.
Visualise workforce data using charts.
Export analysis results to Excel.
Tools and Technologies
Python — data analysis and calculations
Pandas — data cleaning, transformation, and aggregation
Matplotlib — data visualisation
Seaborn — chart styling
Google Colab — cloud-based Python development
DBeaver / MySQL — database exploration and data extraction
Excel — analysis reports and results

Dataset
The project uses four related tables exported from a MySQL database:

employees — employee details and contracted hours
departments — department and cost-centre information
timesheets — recorded hours, utilisation, and approval status
timesheet_weeks — weekly reporting periods

Analysis and Visualisations

The project includes:

Department Hours Analysis — compares total recorded hours across departments.
Labour Cost Analysis — estimates labour costs using hourly rates.
Weekly Cost Trends — visualises estimated labour costs over time.
Employee Hours Comparison — compares recorded hours against contracted hours.
Department Hours Distribution — shows each department's share of recorded hours.
Excel Reporting — exports detailed data and summary tables.

Methodology

Timesheet records are combined with employee, department, and week information using Pandas. Aggregations are then used to calculate department totals, weekly trends, employee hours, and estimated labour costs.

Cost assumption: The current prototype uses an illustrative hourly rate of 30 currency units per hour. These figures are estimates, not actual payroll costs. Accurate cost reporting requires verified employee pay rates and appropriate treatment of overtime and other employment costs.

How to Run the Project

Open the .py in preferrred editor.
Upload the required CSV files.
Run the commands in order.
Review the summary tables and charts.
Export the final Excel report.

Install the required libraries if needed:

pip install pandas matplotlib seaborn openpyxl


