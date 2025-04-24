# Customer Call Report

## Project Objective 
This repository contains an Excel workbook designed to analyze and visualize customer call center performance. It includes raw data, pivot tables, and dashboards to track key performance indicators (KPIs).

# Contents
- <a  href="https://github.com/hariharanr8/Customer_call_report/blob/main/README.md#Data-Column">Data Column</a>
- <a  href="https://github.com/hariharanr8/Customer_call_report/blob/main/README.md#Process">Process</a>
- <a  href="https://github.com/hariharanr8/Customer_call_report/blob/main/README.md#Usage">Usage</a>
- <a  href="https://github.com/hariharanr8/Customer_call_report/blob/main/README.md#Features">Features</a>
- <a  href="https://github.com/hariharanr8/Customer_call_report/blob/main/README.md#Recommendations">Recommendations</a>
- <a  href="https://github.com/hariharanr8/Customer_call_report/blob/main/README.md#Final-Conclusion">Final Conclusion</a>
## Dataset Used
- <a href="https://github.com/hariharanr8/Customer_call_report/blob/main/project1(customercallreport)Data.xlsx">Dataset</a>
- <a href="https://github.com/hariharanr8/Customer_call_report/blob/main/project1(customercallreport).xlsx">Dashboard</a>
## Data Column
(First, review the data in the Excel file. Usually, you'll find columns to make an Ideas)</br>
       1.Data: Raw call center logs for analysis.</br>
       2.dashboard: Visualizations of key metrics and trends.</br>
       3.pivot: Aggregated data in pivot table format(Filter from Data)</br>
       5.Logo:Placeholder or Logo used in Dashboard</br>
## Process
### Step 1- Clean the Data
       Before dashboarding, clean your data:
              Remove empty rows/columns.
              Ensure dates are in proper date format.
              Standardize column headers (e.g., no typos, consistent capitalization).
              Replace missing values or blanks if necessary.
### Step 2- Define Dashboard Metrics
       Common dashboard KPIs for a customer call report:
              Total Calls
              Calls by Type (Bar/Donut Chart)
              Average Call Duration
              Calls Per Day (Line/Column Chart)
              Calls per Agent (Bar Chart)
              Resolution Rate (e.g., % Resolved)
### Step 3- Create Pivot Tables
       Use Excel's Insert > PivotTable:
       1.Total Calls per Day:
          Rows: Date
          Values: Count of Call ID or Customer Name
       2.Calls by Agent:
          Rows: Agent Name
          Values: Count of Call ID
       3.Call Type Distribution:
          Rows: Call Type
          Values: Count of Call ID
       4.Average Call Duration by Agent or Type:
          Rows: Agent Name or Call Type
          Values: Average of Call Duration
### Step 4- Create the Dashboard
       On a new Excel sheet:
          Add charts from PivotTables (Insert > Chart).
          Use slicers for interactivity (Insert > Slicer).
          Connect the slicers to all charts.
Arrange the charts neatly and give it a clean title like "Customer Call Center Dashboard".
![project1image](https://github.com/user-attachments/assets/eb8c792c-0de1-4c04-9dda-d8b864106815)

### Step 7: Documentation & Reporting
Summarize key findings and insights in:</br>
    -Dashboard visuals</br>
    -Readme or PDF report</br>
    -Executive summary for stakeholders</br>

## Usage
       1.Open the workbook in Excel.
       2.Use the "Data" sheet for raw call analysis.
       3.Review the "dashboard" for visual summaries.
       4.Explore "pivot" for aggregated insights.

## Features
       1.Comprehensive call log dataset.
       2.Pre-built pivot tables for quick summaries.
       3.Visual dashboards for insights into KPIs.

## Recommendations
       1.Rename unnamed columns for clarity.
       2.Ensure consistent formatting across sheets.
       3.Customize dashboards for specific use cases.
## Final Conclusion
In conclusion, the customer call report dashboard provides a clear, data-driven overview of call center operations. It highlights call volume trends, representative performance, caller demographics, and customer satisfaction levels. The insights reveal opportunities to  optimize staffing during peak periods, improve service quality across locations, and tailor strategies based on customer profiles.  By leveraging this information, the organization can enhance overall efficiency,  deliver better customer experiences, and make more informed operational decisions.
