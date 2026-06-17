# HR Analytics Dashboard – Employee Attrition Analysis

## Project Overview

This project analyzes employee data to understand workforce trends and identify factors contributing to employee attrition. The analysis combines Exploratory Data Analysis (EDA), correlation analysis, and an interactive Power BI dashboard to provide actionable HR insights.

## Objectives

* Analyze employee demographics, salary, and tenure data.
* Identify patterns in employee attrition.
* Compare attrition across departments and job roles.
* Perform correlation analysis to uncover key drivers of attrition.
* Build HR KPIs for workforce monitoring.
* Create an interactive dashboard to support decision-making.

## Tools Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Google Colab
* Power BI

## Dataset Features

The dataset contains employee information such as:

* Age
* Gender
* Marital Status
* Department
* Job Role
* Monthly Income
* Years at Company
* Years Since Last Promotion
* Salary Hike Percentage
* Overtime Status
* Attrition Status

## Data Analysis Process

### 1. Data Cleaning

* Checked missing values and duplicates
* Standardized column names
* Prepared data for analysis and visualization

  <img width="630" height="708" alt="Screenshot 2026-06-17 193747" src="https://github.com/user-attachments/assets/e4094b0f-361a-4dc7-aaac-082e33c971aa" />


### 2. Exploratory Data Analysis (EDA)

* Employee distribution by age group
* Attrition by gender and marital status
* Department-wise attrition analysis
* Job role-wise attrition analysis
* Salary distribution analysis
* Tenure and promotion impact analysis

  <img width="863" height="687" alt="image" src="https://github.com/user-attachments/assets/cb427ab9-41c1-409d-8ae0-eb5cd04aeca0" />


### 3. Correlation Analysis

Correlation analysis was performed to identify relationships between employee attributes and attrition-related factors.

<img width="777" height="675" alt="image" src="https://github.com/user-attachments/assets/1b55f5ca-5285-4d5a-bcd9-e15a1b69be15" />


### 4. Dashboard Development

An interactive Power BI dashboard was created with filters for:

* Department
* Job Role

## Dashboard Pages

### Page 1: Attrition Overview

Key metrics:

* Total Employees: 1470
* Active Employees: 1242
* Inactive Employees: 238
* Average Salary: 6504.99
* Average Tenure: 7.01 Years
* Attrition Rate: 16.08%

  <img width="828" height="697" alt="Screenshot 2026-06-17 192503" src="https://github.com/user-attachments/assets/6ffb2010-4f9b-418c-956c-3a75b7f3c62f" />


Insights:

* Employees aged 18–25 show the highest attrition.
* Male employees experience slightly higher attrition than females.
* Sales department records the highest attrition.
* Sales Representatives and Laboratory Technicians show the highest employee turnover.

### Page 2: Attrition Drivers and Insights

Key drivers analyzed:

* Salary Slab
* Overtime
* Job Level
* Tenure
* Promotion Gap

<img width="830" height="697" alt="Screenshot 2026-06-17 192514" src="https://github.com/user-attachments/assets/2493c587-fa54-49b9-ac43-c072d7921a4d" />


Insights:

* Employees in lower salary brackets are more likely to leave.
* Overtime employees show higher attrition rates.
* Lower job levels experience greater employee turnover.
* Employees with limited promotion opportunities are more likely to leave.
* Recently joined employees show higher attrition compared to long-tenured employees.

## Business Recommendations

* Improve retention programs for younger employees.
* Review compensation for lower salary groups.
* Monitor overtime workload and employee well-being.
* Strengthen career progression and promotion pathways.
* Focus retention efforts on Sales and high-risk job roles.

## Project Files

* Power BI Dashboard (.pbix)
* Dataset
* EDA and Correlation Analysis Notebook
* Dashboard Screenshots
* README.md

## Conclusion

The project highlights the major factors influencing employee attrition and demonstrates how HR analytics can support data-driven workforce management decisions.
