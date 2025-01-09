# HR Analytics Dashboard

## Introduction
This project analyzes MeriSkill's HR data to provide insights into demographics, turnover patterns, and employee wellness. The dashboard is designed to help organizations make informed strategic decisions to improve workforce retention, satisfaction, and productivity.

---

## Objectives
1. **Demographics**: Analyze age groups, gender distribution, and job roles.
2. **Turnover Analysis**: Investigate attrition rates, reasons, and patterns across multiple dimensions.
3. **Employee Wellness**: Study stress levels, satisfaction, engagement, and wellness programs.

---

## Key Features
- **Interactive Dashboards**:  
  - **Demographics Overview**: Insights into employee age, gender, marital status, and education field.  
  - **Turnover Analysis**: Attrition trends by job role, business travel, and years in the current role.  
  - **Employee Wellness**: Satisfaction scores, work-life balance, and job involvement.  

- **Visualizations**:
  - Clustered bar, stacked column, and donut charts for quick insights.
  - Correlation analysis and grouping for effective data representation.
  - Comprehensive pages covering different aspects of HR data:
    - Page 1: Overview.
    - Page 2: Demographics Insights.
    - Page 3: Turnover Analysis I.
    - Page 4: Turnover Analysis II.
    - Page 5: Employee Wellness.

---

## Tools & Technologies
- **Power BI**: Used for creating interactive and visually appealing dashboards.
- **Data Cleaning**:
  - Removing duplicates and handling null values.
  - Standardizing columns for consistency.
  - Grouping and categorizing values for analysis (e.g., work-life balance, distance from home).
  
---

## Data Insights
- Total employees analyzed: **1470**.
- Key metrics include:
  - **Attrition count**: 237 employees.
  - **Gender distribution**: 60% male and 40% female.
  - **Department breakdown**: Research & Development, Sales, and HR.
  - **Business travel frequency**: Frequent, rare, and non-travel.
- Attrition influenced by:
  - Age groups: 18–30, 31–45, 46–60.
  - Satisfaction levels: Environmental, relationship, job involvement.
  - Overtime status and distance from home.

---

### Repository Structure

HR-Analytics-Dashboard/
├── **Data/**  
│   ├── `HR_Analytics_Dataset.csv` - Cleaned dataset used in Power BI  
│   └── `Sample_Data_Dictionary.xlsx` - Column definitions and data types  
├── **PowerBI_Files/**  
│   └── `HR_Analytics_Dashboard.pbix` - Power BI dashboard file  
├── **Visualizations/**  
│   ├── `Page1_Overview.png` - Screenshot of Overview dashboard  
│   ├── `Page2_Demographic_Insights.png` - Screenshot of Demographics Insights  
│   ├── `Page3_Turnover_Analysis1.png` - Screenshot of Turnover Analysis I  
│   ├── `Page4_Turnover_Analysis2.png` - Screenshot of Turnover Analysis II  
│   └── `Page5_Employee_Wellness.png` - Screenshot of Employee Wellness  
├── **Scripts/**  
│   ├── `Data_Cleaning_Script.R` - Script for cleaning and preprocessing  
│   └── `Data_Transformation_Steps.md` - Manual transformation steps in Power BI  
├── **Documentation/**  
│   ├── `Dashboard_Design.md` - Explanation of dashboard design choices  
│   ├── `Data_Preprocessing.md` - Details of cleaning and transformations  
│   ├── `Insights_And_Interpretations.md` - Key insights from the dashboards  
│   └── `Visuals_Details.md` - Description of all visualizations  
├── `README.md` - Project documentation  
└── `.gitignore` - To exclude unnecessary files  

### Outputs

The repository includes the following outputs showcasing key insights from the HR Analytics project:

#### 1. Page 1: Overview Dashboard
![Overview Dashboard]
A high-level summary of employee demographics, attrition trends, and key statistics.

#### 2. Page 2: Demographics Insights
![Demographics Insights]
Explores age groups, gender distribution, marital status, and department-wise breakdowns.

#### 3. Page 3: Turnover Analysis I
![Turnover Analysis I]
Analyzes attrition patterns by job role, business travel frequency, and years in the current role.

#### 4. Page 4: Turnover Analysis II
![Turnover Analysis II] 
Focuses on attrition trends by job level, performance ratings, and overtime.

#### 5. Page 5: Employee Wellness
![Employee Wellness] 
Highlights work-life balance, job satisfaction, and employee engagement metrics.
