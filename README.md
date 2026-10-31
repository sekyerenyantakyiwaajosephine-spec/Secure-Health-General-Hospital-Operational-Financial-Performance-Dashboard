# Secure Health General Hospital: Operational & Financial Performance Dashboard
 ## Introduction
 ![Introduction Image](Introduction%20Image.png)

This project focuses on analyzing patient data for Secure Health General Hospital. The hospital's management noticed fluctuations in patient admissions and a growing concern over unpaid medical bills. However, because their data was scattered, they lacked a single, clear view of their overall operational and financial health.
As a Data Analyst, my goal was to step in, clean the raw data, and build an interactive dashboard. This tool helps hospital management instantly see how the hospital is performing, identify where money is being lost, and make faster, data-driven decisions.

## Tools Used    
**Microsoft Excel:** Used for data cleaning, feature engineering (formulas), Pivot Tables, and designing the interactive dashboard.

 ## About the Dataset
The dataset contains 1,000 records spanning from January 2024 to December 2025, where every row represents a single patient visit (meaning one patient could appear multiple times). The data is divided into three main categories:

- **Patient Info:** Age, Gender, and Age Category.
  
-	**Visit Details:** Admission and Discharge dates, Department (e.g., Cardiology, Emergency), and Diagnosis.
  
- **Financials:** Total Bill, Paid Amount, Payment Status, and Insurance Coverage percentages.
  
## Problem Statement
The management at Secure Health General Hospital lacked a consolidated report to track operational performance and financial leaks. To solve this, I built a dashboard that answers the following key business questions:

-	How many total patient visits has the hospital recorded?
  
-	Which departments receive the highest number of patients?
  
-	How much money has been billed, and how much remains outstanding?
  
-	What is the average length of stay across different departments?
  
-	How does insurance coverage vary across the hospital?
  
-	Which age groups account for the highest number of visits?
  
## Steps Taken (Data Preparation)
To transform the raw data into a usable dashboard, I followed these steps:
- **Data Cleaning:** Checked for missing values, duplicates, and ensured all date formats were consistent.
  
- **Feature Engineering:** Created new columns using Excel formulas. For example, I used DATEDIF to calculate the Average Stay Length and IF statements to calculate the Patient's Responsibility Amount and determine Age Categories.
  
- **Data Aggregation:** Built Pivot Tables to summarize the total bills, paid amounts, and patient counts by department and age group.
  
- **Dashboard Design:** Connected Pivot Charts to the tables and added Slicers (filters) for "Year" and "Department" so management can easily interact with the data.
  
## Visualization

![Performance Dashboard](Performance%20Dashboard%20for%20Secure%20Health%20Hosp..png)

Dashboard Overview:
The dashboard features high-level KPI cards (Total Patients, Total Bill, Paid Amount, Average Stay, and Insurance Coverage) for a quick summary. It uses bar charts to show patient traffic by Department and Age Group, a donut chart to visualize Payment Status, and a line chart to track Admission Trends over time.

## Key Insights
Here is what the data reveals about the hospital's performance:
1. **Total Patient Visits**: The hospital recorded 1,000 visits.
   - Period covered: January 2024 to December 2025
   - Average stay per visit: 4.8 days

   Over two years, the hospital handled 1,000 patient visits. This gives us a clear base to measure everything else against, from money to staffing.

2. **Revenue and Payment Gap**: A large part of the money billed has not been collected.
   - Total billed: $8.05 million
   - Total collected: $4.56 million
   - Unpaid amount: about $3.5 million
   - About 57% of bills are fully paid
   - About 43% of bills are Pending or Partially Paid

   Almost half of all bills are not fully paid. That leaves about $3.5 million uncollected, which makes this the biggest money problem in the data.

3. **Busiest Departments**: General and Emergency take in the most patients.
   - General: 252 visits (most visited)
   - Emergency: 190 visits
   - Orthopedics: 159 visits
   - Pediatrics: 153 visits
   - Cardiology: 152 visits
   - Neurology: 94 visits (least visited)
   - Together, General and Emergency handle about 44% of all visits

   General and Emergency carry the heaviest workload in the hospital. These two teams need the most staff and resources to keep up with patient demand.

4. **Length of Stay**: Orthopedics patients stay much longer than others.
   - Overall average stay: 4.8 days
   - Orthopedics: 8.3 days (longest)
   - Emergency: 2 days (shortest)

   Orthopedics patients stay about 3.5 days longer than the hospital average. The data does not show the reason, so this department needs a closer look.

5. **Patient Demographics**: The hospital mostly serves older adults.
   - Ages 51 to 65: 235 visits
   - Ages 66 and above: 232 visits
   - Ages 36 to 50: 210 visits
   - Ages 18 to 35: 170 visits
   - Under 18: 153 visits
   - Ages 51 and above make up almost half of all visits

   Older adults use the hospital more than any other age group. Their health needs should guide how the hospital plans its services.

6. **Gender Balance**: Visits are shared almost equally between women and men.
   - Female: 51%
   - Male: 49%

   Women and men visit the hospital in almost equal numbers. This means services do not need to lean towards one group.

7. **Insurance Coverage**: Insurance pays most of each bill.
   - Average insurance coverage: 75%

   On average, insurance covers 75% of a bill. Patients are left to pay the other 25%.

8. **Seasonal Trends**: Visits are steady, with a few busy months.
   - Admissions stay fairly stable across 2024 and 2025
   - Spikes happen in July, October and December

   Patient numbers stay steady for most of the year. The hospital can plan staff and beds ahead of July, October and December, when visits rise.
## Recommendations
Based on the insights, I recommend the following actions for management:
-	**Fix the Billing Gap:** The hospital needs a stronger follow-up system for the 43% of unpaid bills. Offering flexible installment plans to patients could help recover the missing $3.5 million faster.
  
-	**Resource Allocation:** Since General and Emergency are the busiest departments, management should ensure these teams have optimal staffing and resources to prevent burnout.
  
-	**Investigate Orthopedics:** Management should audit the Orthopedics department to understand the 8.3-day average stay. Are there administrative delays in discharging patients, or is it purely medical?
  
- **Senior Care Focus:** Almost half of all visits come from older adults. The hospital could start care programs made just for them. Simple health check packages could also help them stay well and avoid long hospital stays.
  
 ## Conclusion
This dashboard provides Secure Health General Hospital with a clear, actionable view of its operations. While the hospital is bringing in a steady stream of patients, the high rate of unpaid bills is a clear warning sign. By using this dashboard to track payments closely and manage high-traffic departments, the hospital can significantly improve both its patient care and its financial health.


