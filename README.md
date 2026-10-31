# Secure Health General Hospital: Operational & Financial Performance Dashboard

## Introduction
![](Introduction_image.png)
This project focuses on analyzing patient data for Secure Life General Hospital. The hospital's management noticed fluctuations in-patient admissions and a growing concern over unpaid medical bills. However, because their data was scattered, they lacked a single, clear view of their overall operational and financial health.
As a Data Analyst, my goal was to step in, clean the raw data, and build an interactive dashboard. This tool helps hospital management instantly see how the hospital is performing, identify where money is being lost, and make faster, data-driven decisions.

Tools Used
Microsoft Excel: Used for data cleaning, feature engineering (formulas), Pivot Tables, and designing the interactive dashboard.
## About the Dataset

The dataset contains 1,000 records spanning from January 2024 to December 2025, where every row represents a single patient visit (meaning one patient could appear multiple times). The data is divided into three main categories:
•	Patient Info: Age, Gender, and Age Category.
•	Visit Details: Admission and Discharge dates, Department (e.g., Cardiology, Emergency), and Diagnosis.
•	Financials: Total Bill, Paid Amount, Payment Status, and Insurance Coverage percentages.

## Problem Statement
The management at Secure Life General Hospital lacked a consolidated report to track operational performance and financial leaks. To solve this, I built a dashboard that answers the following key business questions:
•	How many total patient visits has the hospital recorded?
•	Which departments receive the highest number of patients?
•	How much money has been billed, and how much remains outstanding?
•	What is the average length of stay across different departments?
•	How does insurance coverage vary across the hospital?
•	Which age groups account for the highest number of visits?

## Steps Taken (Data Preparation)
To transform the raw data into a usable dashboard, I followed these steps:
Data Cleaning: Checked for missing values, duplicates, and ensured all date formats were consistent.
Feature Engineering: Created new columns using Excel formulas. For example, I used DATEDIF to calculate the Average Stay Length and IF statements to calculate the Patient's Responsibility Amount and determine Age Categories.
Data Aggregation: Built Pivot Tables to summarize the total bills, paid amounts, and patient counts by department and age group.
Dashboard Design: Connected Pivot Charts to the tables and added Slicers (filters) for "Year" and "Department" so management can easily interact with the data.

## Visualization
Dashboard Overview:
The dashboard features high-level KPI cards (Total Patients, Total Bill, Paid Amount, Average Stay, and Insurance Coverage) for a quick summary. It uses bar charts to show patient traffic by Department and Age Group, a donut chart to visualize Payment Status, and a line chart to track Admission Trends over time.

## Key Insights
Here is what the data reveals about the hospital's performance:
•	Revenue & Payment Gap: The hospital recorded 1,000 visits and billed a total of $8.05 million. However, only $4.56 million has been collected. This means 43% of bills are either Pending or Partially Paid, representing a massive financial leak.
•	Busiest Departments: The General department is the most visited (252 patients), closely followed by Emergency (190 patients). Neurology is the least visited (94 patients).
•	Length of Stay: The overall average stay is 4.8 days. Orthopedics patients stay the longest (averaging 8.3 days), which is common for surgery and rehab, while Emergency patients have the shortest stays (2 days).
•	Patient Demographics: The hospital primarily serves older adults. Patients aged 51–65 (235 visits) and 66 & Above (232 visits) make up almost half of all hospital traffic.
•	Seasonal Trends: Admissions are relatively stable across 2024 and 2025, but there are noticeable spikes in patient visits during July, October, and December.

## Recommendations
Based on the insights, I recommend the following actions for management:
•	Fix the Billing Gap: The hospital needs a stronger follow-up system for the 43% of unpaid bills. Offering flexible installment plans to patients could help recover the missing $3.4 million faster.
•	Resource Allocation: Since General and Emergency are the busiest departments, management should ensure these teams have optimal staffing and resources to prevent burnout.
•	Investigate Orthopedics: Management should audit the Orthopedics department to understand the 8.3-day average stay. Are there administrative delays in discharging patients, or is it purely medical?
•	Senior Care Focus: With older adults making up the majority of visits, the hospital could introduce specialized geriatric care programs or preventive health packages tailored to them.

## Conclusion
This dashboard provides Secure Life General Hospital with a clear, actionable view of its operations. While the hospital is bringing in a steady stream of patients, the high rate of unpaid bills is a clear warning sign. By using this dashboard to track payments closely and manage high-traffic departments, the hospital can significantly improve both its patient care and its financial health.

