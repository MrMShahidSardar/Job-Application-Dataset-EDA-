# 📊 Job Application Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs a complete **Exploratory Data Analysis (EDA)** on a personal **Job Application Dataset** consisting of 80 job applications.  
The goal is to analyze application patterns, identify trends, and extract meaningful insights that can improve future job search strategies.

---

## 📂 Dataset Structure
- **Rows:** 80 job applications  
- **Columns:** 13  
- **Types:** Mostly categorical (`object`) + 1 datetime (`Date`) + 1 numeric (`S.No`)

### 🔑 Key Fields
- **Job Context:** `State`, `Job Type`, `Job Title`, `Company Name`  
- **Application Source:** `Job Portal`, `On Company Website`  
- **Documents:** `CV Used`, `CV Version?`, `Cover Letter Used`, `Cover Letter Version?`  
- **Target Variable:** `Application Status`

---

## 🛠️ EDA Steps

### Step 1: Dataset Structure
- Checked number of rows, columns, and datatypes.  
- Grouped variables into **Job Context**, **Application Source**, **Documents**, and **Target Variable**.

### Step 2: Data Quality Checks
- ✅ No missing values.  
- Checked for duplicate applications (`Company + Job Title + Date`).  
- Reviewed categorical consistency (e.g., `LinkedIn` vs `Linkedin`, `StepStone` vs `Stepstone`).  

### Step 3: Univariate Analysis
- **Application Status:** Distribution and success ratio.  
- **Job Portal:** LinkedIn vs StepStone performance.  
- **State:** Applications across German states.  
- **Job Type & Job Title:** Most applied roles.  
- **Company Name:** Top companies targeted.  
- **On Company Website:** Direct vs portal applications.  
- **Documents:** CV and Cover Letter usage.  
- **Date:** Monthly application trends.  

### Step 4: Bivariate Analysis
- **Application Status vs Job Portal** → Which portal yields better outcomes?  
- **Application Status vs State** → Regions with higher response rates.  
- **Application Status vs Job Type** → Which roles are more responsive?  
- **Application Status vs CV/Cover Letter Version** → Effect of document variations.  
- **Date vs Application Status** → Response rate changes over time.  

### Step 5: Time-Series Trends
- **Cumulative Applications:** Growth over time.  
- **Rolling Average (7-day):** Consistency of applications.  

### Step 6: Key Insights
- **Success Rate:** % of applications that moved beyond submission.  
- **Best Portal:** Platform with the highest success rate.  
- **Best State/Region:** Geographic region with better responses.  
- **Document Version Effect:** Identify most effective CV/Cover Letter.  
- **Application Consistency:** Determine whether applications were steady or bursty.  

---

## 📈 Tools & Libraries
- **Python**  
- **Pandas** → Data manipulation  
- **Matplotlib / Seaborn** → Data visualization  
- **Jupyter Notebook / VS Code** → Analysis environment  

---

## 🚀 Outcome
This EDA provides actionable insights into personal job applications.  
It helps to:
- Optimize application strategy.  
- Identify the most effective job portals and regions.  
- Evaluate the impact of CV/Cover Letter versions.  
- Track consistency and trends in job searching.  

---

## 📌 Next Steps
- Extend EDA with **predictive modeling** (e.g., classification of success likelihood).  
- Build an **interactive dashboard** (Streamlit / Power BI).  
- Automate weekly updates from new job applications.

