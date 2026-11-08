# AI-ML-Jobs-Report
A 4-page dashboard that analyses AI & ML job postings to understand hiring trends, salaries, locations, companies and in-demand skills.

📁 File: Job_analysis_Dashboard.pbix

Report pages
Page	What it shows
Overview	Total Jobs, Average & Median Salary, Remote Job %, monthly hiring trend, jobs by experience level
Location Insights	Jobs and salary by region / country / city using map, treemap, KPI and matrix, with filters for region, experience level and month
Company & Role Insights	Jobs per company by experience level, company ratings, job title vs total jobs (remote / onsite), remote ratio vs salary
Skill & Hiring Insights	Most in-demand skills by experience level, salary by skill and remote status, average skills per job
Key insights

🔧 Fill these from your dashboard:

Total jobs analysed: [value], average salary [value], [x]% of jobs are remote
Top hiring country: [country], highest paying country: [country]
Most in-demand skill: [skill]
Salary jump from entry to senior level: [x]%
Data model

Star schema:

Dim_Date ─────┐
Dim_Locations ─┤
Dim_Companies ─┼── Fact_Jobs ── Fact_Job_Skills ── Dim_Skills

Key DAX measures: TotalJobs, AvgSalary, MedianSalary, RemoteJob%, AvgSalaryByExperience, AvgSalaryByCountry, JobsPerCompany, CompanyAvgRating, SkillUsageCount, AvgSkillPerJob

Overview Location Insights Company & Role Insights Skill & Hiring Insights

🛠️ Skills demonstrated
Data cleaning and transformation (Power Query)
Data modelling (star schema, relationships)
DAX measures and KPIs
Interactive visuals: maps, treemaps, waterfall, funnel, ribbon, scatter, KPI cards
Slicers, filters and dashboard storytelling
▶️ How to open
Install Power BI Desktop (free, Windows only)
Clone or download this repository
Open the .pbix file of the project you want
