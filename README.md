# hr-attrition-eda

# HR Employee Attrition Analysis — Python EDA

An exploratory data analysis (EDA) project investigating why employees
leave organisations, using the IBM HR Analytics dataset. Built using
Python, Pandas, Matplotlib, and Seaborn in Google Colab.

---

## Problem Statement

Employee attrition is one of the costliest challenges for any organisation.
Replacing an employee can cost up to 2x their annual salary. This project
analyses 1,470 employee records to identify the key factors driving
attrition — and recommends where HR teams should focus their retention
efforts.

---

## Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Matplotlib | Base visualisations |
| Seaborn | Statistical charts and heatmaps |
| Google Colab | Development environment |
| GitHub | Version control and portfolio hosting |

---

## Dataset

- **Source:** IBM HR Analytics Employee Attrition Dataset (public domain)
- **Rows:** 1,470 employees
- **Columns:** 35 features including Age, Department, MonthlyIncome,
  JobSatisfaction, OverTime, YearsAtCompany, and Attrition (target)
- **Attrition column:** Yes / No → converted to 1 / 0 for analysis

---

## Project Structure

```
hr-attrition-eda/
│
├── README.md                  ← Project overview (this file)
└── HR_Attrition_EDA.ipynb     ← Full EDA notebook (11 cells)
```

---

## Analysis Performed

### 1. Data Loading & Exploration
- Loaded dataset from public GitHub source using Pandas
- Checked shape, column types, missing values, and duplicates
- Converted Attrition column from Yes/No to binary 1/0

### 2. Data Cleaning
- Removed duplicate rows
- Ensured correct data types for analysis
- Verified zero missing values across all 35 columns

### 3. Visualisations
- **Attrition overview** — overall count of employees who left vs stayed
- **Attrition by Department** — which department loses the most employees
- **Monthly Income vs Attrition** — income difference between leavers and stayers
- **Job Satisfaction vs Attrition** — satisfaction score breakdown by attrition
- **Overtime vs Attrition** — impact of overtime on employee exit
- **Correlation Heatmap** — relationships between all numeric variables

---

## Key Findings

| # | Finding |
|---|---|
| 1 | Overall attrition rate is **16.12%** — roughly 1 in 6 employees left |
| 2 | **Sales department** has the highest attrition rate among all departments |
| 3 | Employees who left earned **significantly lower monthly income** than those who stayed |
| 4 | Employees with **JobSatisfaction score of 1 (lowest)** leave at the highest rate |
| 5 | Employees working **overtime leave at nearly double the rate** of those who don't |
| 6 | **MonthlyIncome and JobLevel** have the strongest negative correlation with attrition |

---

## Business Recommendation

> Prioritise retention efforts on Sales department employees who have
> a JobSatisfaction score of 1 or 2, are working overtime, and earn
> below the department median income. These employees represent the
> highest attrition risk and the greatest opportunity for targeted
> intervention.

---

## How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Upload `HR_Attrition_EDA.ipynb`
4. Click **Runtime → Run all**
5. All charts will render automatically

---

## Author

**Sakthi Aishvaryaa Chandrasekar** — Aspiring Data Analyst  
B.Tech Biotechnology | PGDM Business Analytics (Pursuing)  
SQL | Python | Power BI | Logistics Domain  
📍 Chennai, India  
🔗 [LinkedIn](https://linkedin.com/in/sakthi-aishvaryaa-chandrasekar)
🐙 [GitHub](https://github.com/sakthiaishvaryaa-analytics)

---

## Other Projects

| Project | Tools | Link |
|---|---|---|
| Gulf Freight Operations — SQL Analysis | SQL, MySQL | [View →](https://github.com/sakthiaishvaryaa-analytics/gulf-freight-sql-analysis) |
| HR Employee Attrition — Python EDA | Python, Pandas, Seaborn | You are here |
| Power BI Sales Dashboard | Power BI, DAX | Coming soon |
