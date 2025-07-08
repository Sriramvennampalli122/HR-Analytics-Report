# 📊 HR Analytics Report: Employee Attrition Study

Welcome to the HR Analytics project! This repository presents a data-driven exploration of employee attrition using key organizational metrics such as department, salary, satisfaction level, workload, and tenure. The aim is to uncover actionable insights that can guide strategic HR decision-making and improve employee retention.

---

## 🧠 Project Objective

The primary objective is to analyze employee attrition trends and identify patterns that influence employees' decisions to stay or leave. Our focus is on answering:

- Which departments have the highest attrition rates?
- How do salary levels and job satisfaction relate to employee turnover?
- What role does workload and tenure play in attrition?

---

## 📁 Dataset Description

The dataset includes anonymized employee records with the following features:

| Column Name         | Description                                         |
|---------------------|-----------------------------------------------------|
| `department`        | Employee's department within the organization       |
| `salary`            | Salary level categorized as low, medium, or high    |
| `satisfaction_level`| Employee's reported job satisfaction (0–1 scale)    |
| `num_projects`      | Number of projects currently assigned               |
| `time_spent`        | Tenure with the company (in years)                  |
| `attrition`         | Indicates if the employee has left (1) or stayed (0)|

---

## 🛠️ Tools & Technologies

- **Python** 🐍 (Pandas, NumPy, Seaborn, Matplotlib)
- **Jupyter Notebooks**
- **Power BI / Tableau** (optional for dashboarding)
- **Scikit-learn** (for predictive modeling, if extended)

---

## 📈 Key Analyses Performed

- Descriptive statistics & correlation analysis
- Department-wise attrition breakdown
- Satisfaction vs. attrition heatmaps
- Workload vs. satisfaction violin plots
- Predictive modeling for attrition likelihood (optional)

---

## 🔍 Insights Highlight

- Employees with **low satisfaction (< 0.4)** and **high project count (>5)** showed the highest attrition rates.
- **Sales and Support** departments exhibited the most turnover.
- **Salary level** positively correlates with retention—**low-salary groups** are more likely to churn.

---

## 📌 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/hr-analytics-attrition.git
   cd hr-analytics-attrition
