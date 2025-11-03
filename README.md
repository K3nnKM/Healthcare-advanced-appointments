HealthFirst Operational Data Analysis: A deep dive into the patient, clinical and financial operations.

By: Ken K. Macharia, Healthcare Data Analyst.
Tools used: Google Sheets, Pivot Tables, Conditional Formatting, Basic statistics


This project involved the analysis of 750 simulated patient entries who visited the HealthFirst Clinic, in order to improve operational performance of the facility.
 
Executive Summary
This project analyzes 750 simulated outpatient records to identify patterns in patient appointment attendance, clinician efficiency, and financial performance. The goal is to uncover operational bottlenecks and improve both care delivery and revenue collection.

Using Google Sheets for data cleaning, transformation, and analysis, the dataset was enriched with derived metrics including age binning, payment gap, discrepancy in scheduled vs. actual durations, and weekday attendance patterns. Key columns such as gender, insurance, and attendance were normalized to ensure consistency.

Key findings include:

Payment completion varies significantly by insurance type. Publicly insured patients had the lowest out-of-pocket payments, while uninsured ("None") patients were more likely to have unpaid or underpaid bills.
Patients aged 56-60, and 89+ were more likely to miss appointments and underpay charges, suggesting the need for targeted reminders and financial counseling.
Over 20% of appointments had significant discrepancies (≥8 minutes) between scheduled and actual duration.
Clinician workloads were uneven, with some clinicians consistently handling more appointments but also experiencing higher time discrepancies and billing inconsistencies.

This project demonstrates key skills in healthcare data analysis, including:

●	Advanced data cleaning using ARRAYFORMULA, SWITCH, and IFS
●	Feature engineering (age bins, payment categories, discrepancy flags.
●	Exploratory analysis using pivot tables and conditional formatting
●	Visualization of trends by age, insurance, and weekday using Google Sheets charts

Recommendations:

●	Improve follow-up and reminder systems for high-risk groups (elderly, uninsured).
●	Implement pre-visit payment verification or post-visit follow-up for partial payments.
●	Redistribute clinician workloads or review time allocation policies.
●	Introduce Sunday scheduling caps to reduce time discrepancies and staff fatigue.


 
Project Overview
Objective: To understand the clinical appointment procedure, no-show rates, causes of missed appointments, and insurance uptake among patients attending the HealthFirst clinic.
Dataset: 750 simulated patient records containing:PatientID, Age, Gender,Insurance, Date, Time, Clinician, Scheduled duration, Actual duration, Attended, No Show Reasons, Charges
Tools used: Google sheets.
Key Questions: What are the patient demographics? What is the appointment attendance ratio? What are the main causes of missed attendance?  What can be done to improve the appointment attendance ratio? What is the most utilised insurance?

Key Insights
1.	The age group with the most attendance is the 76-80 yr group. The least groups are 86-90 and 56-60 yr groups. More reminders can be sent to the least age groups to improve attendance. 
2.	Most consultation visits are done on Mondays, indicating the need to improve those services during the said day.
3.	Overall, there are few lab reviews done compared to the other visit types. Resources should be redistributed appropriately to avoid wastage and overload in various departments.
4.	Most patients who attend the hospital on Thursday and Friday use public insurance. More patient education and sensitization should be done on those days about private insurance as well.
5.	There is a similar workload among the clinicians, indicating appropriate duty distribution.
6.	There are no major gender discrepancies in visit types and insurance uptake.
7.	The most utilised insurance in the facility is the Public Insurance.

Methods and Skills Demonstrated
Data Analysis
Demographics
1.	52% of the visits were by male patients, while 48% were females
2.	The highest age group was 76-80 years
3.	The least age group was 56-60 years
Clinician Analysis
1.	Dr. B had the least amount of work, only seeing 175 patients, compared to Dr. A who saw 199 patients.
2.	Dr. B had the least percentage of significant discrepancies  at 9.9%, while Nurse D had the highest at 20.99%
Recommendations
Reflections
Through this project, I have been able to improve my Google Sheet skills dramatically, and gained more confidence in using that tool in performing better data analysis. My analytical skills have also gotten a boost and I hope to improve even much further in the future.
Visuals and Tables        
