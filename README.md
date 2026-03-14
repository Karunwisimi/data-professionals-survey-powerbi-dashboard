# Data Professionals Survey Dashboard (Power BI)

## Project Overview
This project was created as part of my preparation for a data analyst internship interview. 

The goal of the project was to analyze survey data from data professionals and uncover insights about salary trends, programming language usage, job roles, and job satisfaction across different regions and experience levels.

This project demonstrates my ability to clean data, model datasets, and build interactive dashboards using Power BI.

---

## Tools Used
- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Dataset Description
The dataset contains survey responses from data professionals and includes fields such as:

- Job Title
- Country
- Annual Salary
- Programming Language
- Job Satisfaction
- Work-Life Balance
- Industry
- Years of Experience

---

## Data Preparation
Data cleaning was performed using Power Query. The following steps were carried out:

- Removed blank rows
- Standardized job titles
- Converted salary fields to numeric format
- Split multi-select programming language fields
- Removed duplicate entries
- Renamed columns for clarity

---

## Data Model
A simple star schema structure was used for the dashboard:

- **Fact Table:** Survey Responses
- **Dimensions:** Country, Job Title, Programming Language

DAX measures were created to calculate metrics such as:
- Total Respondents
- Average Salary
- Average Job Satisfaction

---

## Dashboard Insights

Some key insights from the analysis include:

- Python is the most commonly used programming language among respondents.
- Data Scientists and Data Engineers tend to have higher salary ranges.
- Salary generally increases with years of experience.
- Higher salaries do not always correlate with higher job satisfaction.

---

## Dashboard Preview

![Dashboard Preview](Images/dashboard_preview.png)

---

## Learning Outcome
This project helped me strengthen my skills in:

- Data cleaning using Power Query
- Data modeling using star schema
- Writing basic DAX measures
- Building interactive dashboards in Power BI
- Communicating insights from data

---

## Author
**Simisola Esther Karunwi**

Aspiring Data Analyst | Data Enthusiast

