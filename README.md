# HR Employee Attrition Analysis

## Project Overview

This project analyzes employee attrition using **Python**, **Exploratory Data Analysis (EDA)**, and **Power BI**. The objective is to identify the key factors influencing employee attrition and provide data-driven business recommendations to improve employee retention.

The project covers the complete analytics workflow, including data cleaning, feature engineering, exploratory data analysis, Power Query transformations, interactive dashboard development, and business insights.

---

## Project Objectives

- Analyze employee attrition trends.
- Clean and preprocess HR employee data.
- Perform Exploratory Data Analysis (EDA).
- Identify key factors influencing employee attrition.
- Develop interactive Power BI dashboards.
- Generate business insights and actionable recommendations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI
- Power Query

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- KPI Development
- Dashboard Design
- Power Query Transformations
- Business Insight Generation

---

## Dataset

**Dataset:** IBM HR Employee Attrition Dataset

The dataset contains employee information including:

- Employee Age
- Department
- Job Role
- Monthly Income
- Business Travel
- Overtime
- Job Satisfaction
- Work-Life Balance
- Years at Company
- Performance Rating
- Attrition Status

---

## Project Workflow

### Step 1: Data Understanding

- Dataset exploration
- Shape and structure analysis
- Data type inspection
- Statistical summary
- Unique value analysis

### Step 2: Data Cleaning

- Checked missing values
- Checked duplicate records
- Removed constant columns
- Renamed columns
- Improved categorical values
- Detected outliers using the IQR method
- Created new features:
  - AttritionFlag
  - AgeBand
  - IncomeBand

### Step 3: Exploratory Data Analysis (EDA)

Performed analysis on:

- Overall Attrition
- Department-wise Attrition
- Job Role Attrition
- Gender Analysis
- Age Band Analysis
- Business Travel
- Overtime
- Monthly Income
- Job Satisfaction
- Work-Life Balance
- Correlation Heatmap

### Step 4: Power Query Transformation

Performed data transformations in Power BI using Power Query.

Transformations include:

- Data type conversion
- Renaming columns
- Creating meaningful categorical labels
- Improving data quality for reporting

### Step 5: Power BI Dashboard

Developed two interactive dashboard pages.

**Dashboard Page 1**

- KPI Cards
- Employee Distribution
- Department-wise Attrition
- Gender Analysis
- Age Band Analysis
- Job Role Analysis
- Interactive Slicers

**Dashboard Page 2**

- Overtime Analysis
- Income Band Analysis
- Job Satisfaction
- Work-Life Balance
- Business Travel Analysis
- Education Field Analysis
- Additional KPI Cards

---

# Dashboard Preview

## Dashboard Page 1

![Dashboard Page 1](Dashboard/Dashboard_Page1.png)

## Dashboard Page 2

![Dashboard Page 2](Dashboard/Dashboard_Page2.png)

---

## Key Insights

- Overall employee attrition rate is **16.12%**.
- Employees working overtime experience significantly higher attrition.
- Lower-income employees are more likely to leave the organization.
- Poor work-life balance is associated with increased attrition.
- The Sales department has a higher attrition rate compared to other departments.
- Younger employees exhibit relatively higher attrition rates.

---

## Business Recommendations

- Improve employee work-life balance.
- Reduce excessive overtime.
- Enhance employee engagement initiatives.
- Review compensation for lower-income employees.
- Develop targeted retention strategies for high-risk departments.
- Strengthen career growth and promotion opportunities.

---

## Results

- Successfully analyzed **1,470 employee records**.
- Built a complete end-to-end HR analytics solution.
- Developed **two interactive Power BI dashboard pages**.
- Identified major factors contributing to employee attrition.
- Provided actionable business recommendations to improve employee retention.

---

## Repository Structure

```
HR-Employee-Attrition-Analysis
│
├── Dataset
│   ├── WA_Fn-UseC_-HR-Employee-Attrition.csv
│   └── HR_Attrition_Cleaned.csv
│
├── Notebook
│   └── HR ATTRITION EMPLOYEE.ipynb
│
├── Dashboard
│   ├── HR Analytics.pbix
│   ├── Dashboard_Page1.png
│   └── Dashboard_Page2.png
│
├── Images
│   ├── Power_query1.png
│   ├── Power_query2.png
│   ├── Power_query3.png
│   └── EDA Charts
│
├── Report
│   └── HR ATTRITION EMPLOYEE.pdf
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Project Files

- Original Dataset
- Cleaned Dataset
- Jupyter Notebook
- Power BI Dashboard (.pbix)
- Dashboard Screenshots
- Final Project Report (PDF)

---

## Project Outcome

This project demonstrates an end-to-end HR Analytics workflow, transforming raw employee data into meaningful insights through data cleaning, exploratory analysis, interactive dashboards, and business recommendations that support data-driven HR decision-making.

---

## Author

**Partham Raju**

**Aspiring Data Analyst**

### Skills

- Python
- SQL
- Power BI
- Excel
- Pandas
- NumPy
- Matplotlib
- Seaborn
