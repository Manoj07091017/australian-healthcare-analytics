# 🏥 Australian Healthcare Analytics — End-to-End Data Project

An end-to-end data analytics project analysing Australian public hospital
performance, taking real government data from raw source through to
interactive dashboards. Built to demonstrate the full data analyst skill set
across Python, SQL, and two major BI tools.

## 📊 The Story

Using the ROGS 2026 Public Hospitals dataset, this project answers a question
a health department asks every week: **where are patients waiting longest, and
is performance improving or declining?**

Two headline findings:
- **ED 4-hour completion has collapsed from 70% to 53%** over nine years, with
  the sharpest falls in 2021-22 and 2022-23.
- **Hospital spending shows no meaningful correlation with ED performance**
  (r=0.17, p=0.68) — funding alone doesn't explain outcomes.

## 🗂️ Project Layers

| Layer | Tool | What it demonstrates |
|-------|------|---------------------|
| [1. ETL Pipeline](./1-etl-pipeline) | Python | API/file extraction, data cleaning, validation, loading to SQLite |
| [2. SQL Analytics](./2-sql-analytics) | SQL | Aggregation, CASE logic, window functions (LAG, RANK), CTEs |
| [3. Statistical Analysis](./3-python-analysis) | Python | Trend analysis, correlation testing, data visualisation |
| [4. Tableau Dashboard](./5-tableau-dashboard) | Tableau | Published interactive dashboard |

## 🔗 Live Dashboard

**Tableau Public:** [View the interactive dashboard]([PASTE_YOUR_TABLEAU_LINK_HERE](https://public.tableau.com/app/profile/manoj.sriramappa/viz/Book1_17816618625040/AustralianEmergencyDepartmentPerformance?publish=yes))

## 🛠️ Tech Stack

`Python` `pandas` `SQL` `SQLite` `matplotlib` `seaborn` `scipy`
`Tableau`

## 📁 Data Source

[ROGS 2026 Public Hospitals dataset](https://www.pc.gov.au/ongoing/report-on-government-services/health/public-hospitals)
— Productivity Commission. Covers ED presentations, waiting times, elective
surgery, expenditure, and more across all Australian states, 2015-16 to 2024-25.

## 👤 Author

*Manoj Sriramappa, LinkedIn- https://www.linkedin.com/in/manoj-sriramappa-b404621b3/, and portfolio (Notion) - .*
