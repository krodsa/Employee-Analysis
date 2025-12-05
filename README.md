## 📊 Employee Attrition Analysis

An end-to-end workforce analytics project combining Python-based statistical analysis, predictive modeling, and an interactive Tableau dashboard to uncover drivers of employee turnover and support strategic HR decision-making.

## 📌 Background

Employee turnover poses a significant challenge for organizations, impacting productivity, team morale, and long-term financial performance. This project analyzes an anonymized employee dataset containing key workforce attributes, enabling the exploration of attrition patterns and the development of data-driven insights to support proactive workforce planning.

## 🎯 Project Overview

This project conducts a comprehensive employee attrition analysis by examining demographic characteristics, employment history, compensation details, performance indicators, and job satisfaction metrics.
Key objectives include:

Uncovering key drivers of attrition

Identifying patterns across roles, departments, and demographics

Building predictive techniques to estimate attrition risk

Presenting insights through an interactive dashboard for stakeholders

The project follows a full analytics lifecycle—from data preparation to modeling to visualization.

## 🧠 Executive Summary

The analysis reveals several meaningful insights:

🔹 Key Drivers of Attrition

Job satisfaction and work environment indicators strongly correlate with turnover.

Employees with lower salary ranges and fewer years at the company are more likely to leave.

Specific departments/roles experience disproportionately higher attrition levels.

🔹 Workforce Patterns

Mid-career employees exhibit higher turnover risk than early-tenure employees.

Attrition tends to cluster around certain job roles with high workload-to-reward imbalance.

Satisfaction and performance metrics show predictive value in estimating risk.

🔹 Predictive Modeling

A classification model was trained to estimate the likelihood of attrition based on employee attributes.
The model helps highlight high-risk segments where targeted retention strategies may be most effective.

🔹 Recommended Actions

Prioritize interventions for roles with historically high turnover.

Implement compensation and career-development adjustments for lower-pay bands.

Use predictive modeling to support early identification of at-risk employees.

Enhance job satisfaction drivers (manager support, career pathways, recognition).

## 🛠️ Methodology
1. Data Preparation

Cleaned and validated employee records

Handled missing values and inconsistent entries

Engineered metrics for tenure, compensation grouping, and satisfaction patterns

2. Exploratory Data Analysis (Python)

Summary statistics & distribution analysis

Correlation heatmaps to understand feature relationships

Department and role-level attrition rate calculation

Identified workforce segmentation patterns

3. Predictive Modeling

Built and evaluated classification models (e.g., logistic regression, tree-based models)

Assessed accuracy, precision, recall, and confusion matrix

Analyzed feature importance to understand driver influence

4. Visualization & Storytelling (Tableau)

Designed an interactive attrition dashboard for business stakeholders

Created filters for department, salary, job satisfaction, tenure, and more

Translated modeling insights into accessible visual narratives

This multi-layered approach demonstrates the full analytics workflow expected from modern data analysts.

## 📓 Notebooks & Dashboards
📘 Python Analysis (Full Notebook)

This notebook contains data cleaning, EDA, modeling, and insight generation:
➡️ https://nbviewer.org/github/krodsa/Employee-Analysis/blob/main/Employee%20Attrition%20Analysis.ipynb

📊 Tableau Dashboard (Interactive Visualization)

A business-facing dashboard summarizing KPIs, patterns, and drivers of attrition:
➡️ https://public.tableau.com/app/profile/krodsa/viz/EmployeeAttritionDashboard_17344953568520/AttritionDashboard

📁 Project Repository (Code + Documentation)

➡️ https://github.com/krodsa/Employee-Attrition-Analysis

## 📂 Dataset

The dataset includes anonymized employee records with variables such as:

Demographics (age, gender, marital status)

Tenure and employment history

Job role and department

Compensation and work-life measures

Job satisfaction & environment indicators

Attrition label (yes/no)

This structure ensures realistic workforce insights and supports predictive modeling.

## ⚠️ Limitations

To maintain data integrity and transparency:

Dataset represents anonymized employee information and may not reflect all complexities of live HRIS data.

Self-reported satisfaction metrics can introduce subjective noise.

Findings should be interpreted directionally rather than as prescriptive HR policy.

Nonetheless, the patterns observed closely align with known HR analytics research.

## 🚀 Future Enhancements

Potential next steps:

Build a survival analysis model to estimate time-to-attrition.

Integrate compensation growth, promotion history, and performance review text.

Deploy the predictive model via a lightweight API or web app.

Add departmental benchmarking or industry comparison metrics.

## 📬 Contact

If you’re interested in discussing workforce analytics, predictive modeling, or organizational insights, feel free to connect.
