# Employability Analytics Dashboard - ReadMe

## 📌 Table of Contents
1. [Project Overview](#project-overview)
2. [Team Members and Contributions](#team-members-and-contributions)
3. [Data Sources and Processing](#data-sources-and-processing)
4. [Installation and Setup Instructions](#installation-and-setup-instructions)
5. [Dashboard Features](#dashboard-features)
6. [Screenshots Description](#screenshots-description)
7. [Traceability Matrix](#traceability-matrix)
8. [Submission Checklist](#submission-checklist)

---

## 🧠 Project Overview

This project aims to build an **Employability Analytics Dashboard** that enables users to:
- Analyze job market trends across various IT roles and global locations.
- Evaluate average experience, salary, and work types.
- Compare country-wise salary expectations and role-specific compensation.
- Explore skill demands, qualifications, and application insights interactively.

The dashboard is built using **Microsoft Power BI**. Python and Excel were used to validate, clean, and transform the original datasets.

---

## 👥 Team Members and Contributions

| Member Name | Contribution |
|-------------|--------------|
| Gunda Sai Jayanth, Lahari Gurram   | Data cleaning, dashboard creation, visuals configuration, location mapping, final submission |
| Sai Rahul Brahmadevara | Skill extraction, job title parsing, traceability matrix |
| Supraja | Data modeling, Power BI integration, visuals validation |
| Alankritha | User interface design, testing, feedback incorporation |

---

## 📊 Data Sources and Processing

We used a base dataset `final_it_job_descriptions.csv` and processed it to:
- Normalize job skills and extract individual skills
- Clean salary range to extract min, max, and average values using DAX
- Generate lat-long based on city and country using random values (aligned to country boundaries)
- Create multiple job listings for USA and other countries with logical variations

Tools used:
- Python (Pandas, Faker, NumPy)
- Excel (formulas and filtering)
- Power BI (DAX for column transformation)

---

## 🛠️ Installation and Setup Instructions

1. Ensure **Power BI Desktop** is installed.
2. Open the provided `.pbix` file: `Employability_Analytics.pbix`
3. Make sure all data files are in the same folder:
   - `final_it_job_descriptions.csv`
4. Use the "Transform Data" button to refresh or adjust queries.

---

## 🌐 Dashboard Features

### 🔍 Page 1: Job Market Overview
- KPIs: Total Jobs Posted, Unique Roles, Avg Experience, Active Companies
- Tree map: Count of Job Id by Role
- Bar chart: Experience band breakdown
- Pie chart: Work type and Qualification distribution

<img width="1238" alt="Overview Page" src="https://github.com/user-attachments/assets/ec3a3b35-511a-48e3-b62e-8349543655f5" />

### 📈 Page 2: Skills Insights
- Word cloud of in-demand skills
- Role vs number of jobs
- Qualifications by job count
- Table of Job Titles and Skills

<img width="1238" alt="skill insights page" src="https://github.com/user-attachments/assets/ef011751-4833-4eff-8ee7-c79bae991d89" />

### 💰 Page 3: Salary and Location
- Top 5 high-paying roles
- Avg Salary by Experience
- Salary by Country
- World map with job markers

<img width="1238" alt="salary and location page" src="https://github.com/user-attachments/assets/46f1dce0-169e-40cd-8984-aa8dc4a85999" />


### 🔍 Page 4: Application Explorer
- Drill-down table by job title
- Filters: Role, Salary Range, Job Portal, Skills
- KPIs for matched roles

<img width="1238" alt="application explorer" src="https://github.com/user-attachments/assets/17b81fc6-5d02-4f14-bdcf-e53f496b8e9c" />

---

## 🖼️ Screenshots Description

| Screenshot | Description |
|------------|-------------|
| Job Market Overview | High-level analytics on roles, work type, qualifications |
| Skills Insights | Visualization of trending skills and job distributions |
| Salary and Location | Country-wise salary maps and experience analysis |
| Application Explorer | Role-specific drill-through with advanced filtering |

---

## ✅ Traceability Matrix

| Requirement | Information Needed | Visual/Feature Used | Validation Method |
|-------------|--------------------|---------------------|--------------------|
| Track Job Roles by Work Type | Role, Work Type | Bar chart (Role vs Work Type) | Cross-filter check, visual match |
| Salary Trends by Country | Country, Salary Range | Salary by Country bar chart | Filter country, compare table with bar |
| Skill Demands | Skills column | Word Cloud & Skills table | Check skill match in Job Description |
| Location Mapping | City, Country | Latitude-Longitude Map | Compare geo plots with city |
| Application Filtering | Role, Portal, Skills | Application Explorer Page | Drill-through and filtering validation |

---

## 📦 Submission Checklist

- ✅ final_it_job_descriptions.csv
- ✅ Employability_Analytics.pbix
- ✅ README.md (this file)
- ✅ Screenshot folder (JobMarketOverview.png, SkillsInsights.png, etc.)
- ✅ Any supporting Python/Excel files for data transformation

---

## 📩 Contact

For any clarifications or issues, please contact:gundasaijayanth@gmail.com
