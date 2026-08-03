# HR-Analytics-Dashboard (Interactive Dashboard Creation using Power BI)
## Project Objective:
The HR department wants to create an interactive Power BI report to analyze employee turnover, workforce demographics, and key retention metrics. This dashboard enables HR management and business stakeholders to uncover key drivers behind employee attrition, identify high-risk demographics, and execute data-driven retention strategies.
# Data set
-<a href="https://github.com/yathamadhivardhanreddy15/DATA-ANALYSIS-OF-HR-DASHBOARD/blob/main/HR_Analytics-4.csv">Data set</a>


 # Questions (KPIs):
1.	What are the core summary KPIs (Total Employees, Active Employees, Attrition Count, Attrition Rate %, Average Age, Average Experience)?
2.	Which department experiences the highest attrition volume?
3.	What is the impact of salary brackets (0–3 LPA, 3–6 LPA, 6–10 LPA, 10+ LPA) on turnover?
4.	What is the relationship between job role, job satisfaction levels, and employee attrition?
5.	Which age groups show the highest turnover rates?
6.	What is the gender distribution among attrited employees?
7.	How does total work experience correlate with attrition rates?
8.	What is the overall employee count breakdown by department?


   Dash board- <a href="https://github.com/yathamadhivardhanreddy15/DATA-ANALYSIS-OF-HR-DASHBOARD/blob/main/Screenshot%202026-08-01%20193042.pdf">View Dashboard</a>

# Process (Power BI Workflow):
1.	Data ETL (Power Query): Loaded the dataset into Power Query Editor, performed data cleaning, handled missing values, and established correct data types.
2.	Data Modeling & DAX Measures: Developed DAX (Data Analysis Expressions) measures for dynamic calculations including Attrition Rate %, Active Employees, and Total Headcount.
3.	Report & Visual Design: Built visual layouts using customized Card visuals, Donut charts, Matrix tables, Funnel charts, and Bar charts for clear data storytelling.
4.	Interactivity & Dynamic Filtering: Applied page-level Slicers (Department, Age Slabs) and enabled cross-filtering to allow interactive drill-down analysis across all key workforce metrics.

 # Dashboard
 <img width="483" height="276" alt="Screenshot 2026-08-01 193052" src="https://github.com/user-attachments/assets/4efafea1-8565-4ad7-b9a6-75125510ebad" />

# Project Insights:
•	Gender Breakdown: Male employees represent the majority of turnover (~62.66% male vs. 37.34% female).
•	Age Demographics: The 26–35 age group accounts for the largest proportion of employee churn.
•	Salary Slabs: Employees in lower to mid income tiers (0–3 LPA and 3–6 LPA) exhibit significantly higher departure rates.
•	Job Roles & Satisfaction: Technical roles such as Laboratory Technician (61 total attritions) and Research Scientist (47 total attritions) show elevated turnover, particularly among staff reporting lower satisfaction levels (Ratings 1 & 2).
•	Tenure / Experience: Attrition peaks heavily during early career stages (1–3 years of total experience).
•	Department Proportions: Operations and Sales maintain the largest active workforce counts across the organization.

# Final Conclusion & Recommendations:
To lower employee attrition and boost overall workforce retention, HR leadership should focus on the following Power BI-backed recommendations:
1.	Early-Career Mentorship: Focus retention programs on early-tenure staff (1–3 years experience) within the 26–35 age group by providing structured career development and onboarding support.
2.	Compensation Review: Re-evaluate compensation and benefits structures for entry-to-mid level salary brackets (0–6 LPA), where churn is highest.
3.	Role-Specific Engagement: Conduct targeted workplace reviews and pulse surveys for high-churn roles like Laboratory Technicians and Research Scientists to address job satisfaction bottlenecks.


