
# 💼 HR Analytics – Predict Employee Attrition

## 📌 Project Overview

This project aims to analyze employee attrition using HR data to understand the key factors that contribute to employee resignation. It includes both **machine learning prediction** and a **Power BI dashboard** for visual storytelling.

- 📊 **Tools Used**: Python (Pandas, Seaborn, Sklearn, SHAP), Power BI  
- 📁 **Dataset**: IBM HR Analytics Employee Attrition & Performance  
- 🧠 **Techniques**: Exploratory Data Analysis (EDA), Logistic Regression, Decision Tree, Random Forest, SHAP Analysis  
- 📅 **Duration**: 2 Weeks  

## 🎯 Objectives

- Identify key drivers of employee attrition
- Build classification models to predict resignations
- Create an interactive Power BI dashboard for business decision-makers
- Provide data-driven recommendations to reduce attrition

## 🔍 Project Steps

### 1. Data Preparation & Cleaning
- Removed unnecessary columns (`EmployeeNumber`, `StandardHours`, etc.)
- Label encoded target column `Attrition`
- Performed one-hot encoding for categorical features

### 2. Exploratory Data Analysis (EDA)
- Visualized attrition by age, department, marital status, job role, and overtime
- Found that **younger, single employees with overtime** were more likely to leave

### 3. Machine Learning Modeling
- Applied Logistic Regression, Decision Tree, and Random Forest
- Compared models based on accuracy, recall, F1-score
- Best accuracy from **Logistic Regression** (86%)

### 4. Model Explainability with SHAP
- Used SHAP values to identify top features influencing attrition:
  - DailyRate, Age, DistanceFromHome

### 5. Power BI Dashboard
- Built an interactive HR Attrition Dashboard with dynamic insights
- Key visuals: Attrition by Age, Department, Job Role, OverTime, Marital Status

## 📈 Model Performance

| Model               | Accuracy | Recall (Yes) | F1 Score (Yes) |
|--------------------|----------|--------------|----------------|
| Logistic Regression| 0.86     | 0.34         | 0.44           |
| Decision Tree      | 0.76     | 0.36         | 0.32           |
| Random Forest      | 0.83     | 0.11         | 0.17           |

## 📊 Power BI Dashboard Highlights

- 📌 Dynamic KPIs: Attrition Rate, Count, Total Employees
- 🧩 Visuals:
  - Attrition by Department, Age Group, Job Role
  - Attrition Trends by Age
  - Marital Status and OverTime impact
- ✨ Insight Text Cards that update based on slicer selections

## ✅ Key Takeaways

- **Attrition is highest among employees aged 29–31**
- **Single employees** and those working **OverTime** are more likely to leave
- **Research & Development** has the most resignations
- SHAP values support business decisions by highlighting top drivers

## 📁 Deliverables

- ✔️ Python Code (EDA + Modeling + SHAP)
- ✔️ Power BI Dashboard (`.pbix`)
- ✔️ Final PDF Report (1–2 pages)
- ✔️ `README.md` (this file)


## 🤝 About Me

**Sithu Sunny**  
Aspiring Data Analyst |  
📫 [Connect on LinkedIn](www.linkedin.com/in/sithu-sunny)
