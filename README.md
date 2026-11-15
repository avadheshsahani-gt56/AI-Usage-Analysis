# AI Usage Analysis: Who Uses AI, Which Tools, and Why

**A Python and Power BI Data Analytics Project by Avadhesh Sahani**

## 📌 Project Overview

This project analyzes AI usage patterns among 141 users across 12 countries. It explores which AI tools people use, why they use them, and how AI usage varies across different demographic groups.

## 🎯 Project Objectives

- Identify the most popular AI tools among users.
- Analyze AI adoption across different countries.
- Understand the major purposes of AI usage.
- Compare average daily usage across AI tools.
- Explore AI usage patterns by age, gender, and education level.

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI

## 📊 Dataset Overview

| Description | Details |
|---|---:|
| Total Records | 141 |
| Total Columns | 19 |
| Countries | 12 |
| Missing Values Before Cleaning | 6 |
| Duplicate Records | 0 |

## 🔄 Project Workflow

1. **Data Cleaning:** Cleaned and preprocessed the dataset using Python and Pandas.
2. **Exploratory Data Analysis (EDA):** Performed data analysis, identified trends and patterns, and created visualizations using Python, Pandas, and Matplotlib.
3. **Dashboard Development:** Designed an interactive Power BI dashboard to present key insights and findings.
4. **Project Reporting:** Prepared a detailed project report highlighting the analysis, findings, and recommendations.

## 🧹 Data Cleaning

- Identified 6 missing values in the dataset.
- Used mean imputation for Age, Monthly_AI_Cost, Satisfaction_Score, and Time_Saved_Hours_Per_Week.
- Used median imputation for Monthly_Income because of extreme values.
- Checked for duplicate records.
- Verified missing values after cleaning.
- Exported the cleaned dataset as a CSV file.

## 🔍 Key Findings

- **ChatGPT** is the most popular AI tool, used by 61 users (43.3%).
- **India** has the highest number of users, with 24 users.
- **Coding** is the leading purpose of AI usage (29.1%).
- **Google Gemini** has the highest average daily usage among the top five AI tools.
- Users with a **Bachelor's degree** form the largest education group, with 35 users.
- Users aged **50+** show the highest average daily usage, although this age group has a small sample size.

## 📈 Power BI Dashboard

The interactive dashboard includes:

- Total Users and Average Daily Usage KPI cards.
- AI Tool and Country filters.
- AI tool popularity analysis.
- Country-wise user distribution.
- AI usage by purpose.
- Gender and education-level analysis.
- Average daily usage comparison.

### Dashboard Preview

<img width="1600" height="900" alt="AI usage" src="https://github.com/user-attachments/assets/79e9d8c9-75b6-4add-abbb-47c0d1e6b82d" />


## 📁 Project Structure

```text
AI-Usage-Analysis/
│
├── README.md
│
├── 01_Dataset/
│   ├── AI_Usage_trend.csv
│
├── 02_Python_Analysis/ and cleaning
│   └── AI_Usage_Analysis.ipynb
│
├── 03_Power_BI_Dashboard/
│   ├── Dashboard.png
│   └── AI_Usage_Analysis.pbix
│
└── 04_Project_Report/
    └── AI_Usage_Analysis_Report.pdf
