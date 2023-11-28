# Employee Distribution Analysis
HR Analytics helps us with interpreting organizational data. It finds the people-related trends in the data and allows the HR Department to take the appropriate steps to keep the organization running smoothly and profitably. Attrition in a corporate setup is one of the complex challenges that the people managers and the HRs personnel have to deal with.

## Table of Contents
- [Introduction]
- [Purpose of the Project]
- [Dataset]
- [Project Analysis]
  - [Data Cleaning]
  - [Exploratory Data Analysis (EDA)]
  - Data Visualization
- [Project Insights]
- [Conclusion]

## 1. Introduction
Welcome to the Employee-Distribution! This project contains valuable insights and visualizations derived from an extensive HR dataset spanning from 2000 to 2020, with over 22,000 rows. The data was meticulously cleaned and analyzed using MySQL, and the results are beautifully visualized with Power BI. This comprehensive dashboard aims to answer crucial HR-related questions and shed light on various aspects of the organization's workforce.

## 2. Purpose of the Project 
The major aim of this project is to provide an insightful HR Data Dashboard and help the organization in HR planning and decision-making processes. 

## 3. [Dataset]
This repository contains valuable insights and visualizations derived from an extensive HR dataset spanning from 2000 to 2020, with over 22,000 rows.

## 4. [Project Analysis]
### a. Data Cleaning
In the data cleaning process the following tasks were completed using MySql:
	- Rename the column (ID to employee-id)
  - Change data type
  - Change date format
	- Insert new column “age”
  - Cleaning individual columns.
  - Fill black fields of “term_date” column with zero value.
  - Check for some more Transformations.

### b. Exploratory Data Analysis (EDA) 
    Exploratory data analysis(EDA) is the method to answer and analyse the business questions of this project.

#### Business Questions
1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

**In the following ways the Business questions are analyzed and explored to get an overview of gender distribution in various expect:**

**- Gender Breakdown:** Gender distribution of employees within the company.
**- Race/Ethnicity Breakdown:** Racial and ethnic composition of the workforce.
**- Age Distribution:** Insights into the age distribution of employees.
**- Headquarters vs. Remote Locations:** Understanding the number of employees working at headquarters versus remote locations.
**- Average Employment Length for Terminated Employees:** Finding out the average tenure of terminated employees.
**- Gender Distribution across Departments and Job Titles:** Seeing how gender distribution varies across different departments and job titles.
**- Distribution of Job Titles:** Exploring the distribution of job titles across the company.
**- Highest Turnover Rate by Department:** Identifing the department with the highest turnover rate.
**- Distribution of Employees across Locations (by State):** Learning about the geographic distribution of employees across different states.
**- Employee Count Changes over Time:** Tracking changes in the company's employee count over the years based on hiring and termination dates.
**- Tenure Distribution by Department:** Examining the tenure distribution for each department.

### c. Data Visualization

## 6. Project Insights 
Here are some key findings derived from the HR data analysis:

**Gender Diversity:** The company has more male employees than female employees.
**Race/Ethnicity:** White employees constitute the majority, while Native Hawaiian and American Indian employees are the least represented.
**Age Diversity:** Employees' ages range from 20 to 57, with the majority falling within the 25-34 age group.
**Work Locations:** A considerable number of employees work at the headquarters compared to remote locations.
**Termination Tenure:** The average length of employment for terminated employees is around 7 years.
**Gender Balance in Departments:** While gender distribution across departments is fairly balanced, male employees slightly outnumber female employees in most departments.
**High Turnover Departments:** The Marketing department experiences the highest turnover rate, followed by Training. Research and Development, Support, and Legal departments have the lowest turnover rates.
**Employee Geographic Distribution:** A significant number of employees hail from the state of Ohio.
**Employee Count Trends:** Over the years, the company's employee count has been on the rise.
**Tenure Variation by Department:** The average tenure for each department is approximately 8 years, with Legal and Auditing having the highest, and Services, Sales, and Marketing having the lowest.

## 7. Conclusion
To get started with the HR Data Dashboard and explore the rich visualizations and findings, you can follow these steps:

Clone this repository to your local machine.
Ensure you have the necessary tools installed, such as PostgreSQL and Power BI, to analyze and visualize the data effectively.
Load the provided dataset into your MySQL database.
Open the Power BI file (.pbix) to interact with the pre-built visualizations and answer the key HR questions.
I hope you find this HR Data Dashboard insightful and valuable for your organization's HR planning and decision-making processes. Should you have any questions or feedback, feel free to reach out. Happy analyzing!
