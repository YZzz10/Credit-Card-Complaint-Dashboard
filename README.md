# Credit-Card-Complaint-Dashboard

## Project Objective


## Dataset Used
<a href="">Customer Complaint Dataset</a>  
<a href="">State Mapping Dataset</a>

## KPI Metrics:


## Visualization Overview
- The Trend Chart shows complaint trends over time, with a parameter-driven filter that dynamically adjusts the time granularity between day, week, month, quarter, and year.
- 

## View Dashboard
<a href="">View Dashboard</a> (Please use “See this in Full Screen” if the dashboard elements overlap.)

## Process
- The “Date Received” field was incorrectly interpreted by Tableau as a year-first format. This issue was resolved by converting the field to string and re-parsing it using DATEPARSE("dd-MMM-yy", [Date Received]) to ensure accurate time-series analysis.
- Missing values were handled within the dashboard by excluding null entries to ensure clarity and accuracy in the charts.

## Dashboard
<img width="1600" height="900" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/c245314d-fdc7-45a3-8249-0824aa3fec47" />


## Project Insight
-
-
-

## Final Conclusion
-
-
-
