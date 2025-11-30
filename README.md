This project focuses on analyzing employee headcount (HC) and voluntary attrition within an IT organization using a combination of Python, Streamlit, and data visualization techniques.
It helps HR & Talent Management teams identify patterns, attrition drivers, and improvement areas using a fully interactive dashboard.

All analysis, dashboard logic, and methodology come from:

People Analytics Report 

People Analytics - Talent HC an…

Streamlit Dashboard Code (app.py) 

app (1)

Exploratory Data Analysis Script (exploratory_analysis.py) 

exploratory_analysis

📁 Project Structure
├── app.py                     # Streamlit dashboard app
├── exploratory_analysis.py    # EDA, correlation heatmaps, histograms, boxplots
├── People Analytics Report.docx  # Full documentation & results
└── README.md

🎯 Project Objective

To provide HR leaders with data-driven insights into:

Workforce distribution

Employee attrition patterns

Tenure and job satisfaction impact

Department-wise turnover

Demographic breakdowns

Overtime effects on attrition

The dashboard enables continuous monitoring and updates whenever new HR data is uploaded.

🔍 Key Features
✅ 1. Automated Data Cleaning & Preprocessing

(From exploratory_analysis.py) 

exploratory_analysis

Categorical fields converted into binary variables

Column selection and renaming

Null value check

Duplicate detection

Creation of numeric-only datasets for EDA

✅ 2. Exploratory Data Analysis (EDA)

(From EDA script) 

exploratory_analysis

Correlation heatmaps

Histograms for distribution patterns

Boxplots for outlier detection

Summary statistics (mean, median, skewness)

✅ 3. Headcount (HC) Analysis

Displayed via interactive Streamlit charts (app.py) 

app (1)

:

HC by department

HC by age groups

HC by monthly income

HC by gender

HC by years at company

✅ 4. Attrition Analysis

(From People Analytics Report) 

People Analytics - Talent HC an…

High attrition in Sales department

High attrition among employees with 0–2 years tenure

Younger employees (26–35) show highest turnover

Overtime workers have higher attrition

Higher job satisfaction = lower attrition

Lower job satisfaction & work-life balance = higher attrition

Streamlit dashboard visualizes:

Attrition by department

Attrition by education

Attrition by age

Attrition by gender

Attrition by job role

Attrition by tenure

Attrition by satisfaction scores

Attrition by overtime

📊 Results (From Full Report)
🔥 Key Findings

Sales department shows the highest voluntary attrition.

Early-career employees (0–5 years) leave more often.

Young professionals (26–35) are at highest risk.

Overtime is strongly correlated with higher attrition.

Female employees show lower attrition rates than males.

Low job satisfaction significantly increases turnover risk.

🧠 Recommendations

(based on People Analytics Report) 

People Analytics - Talent HC an…

For HR & Business Leaders:

Conduct deep-dive interviews in Sales to understand root causes.

Focus on retaining new hires, especially university graduates.

Address workload and overtime issues.

Improve job satisfaction with development programs & coaching.

Strengthen diversity hiring — female attrition is lower.

🧰 Tools & Technologies Used
Programming & Analysis

Python

Pandas

NumPy

Matplotlib

Seaborn

Interactive Dashboard

Streamlit (UI, charts, filters)

Statistical Analysis

Correlation Analysis

Summary Statistics

Distribution Analysis

Visualization

Countplots

Histograms

Heatmaps

Boxplots

Documentation & Reporting

Microsoft Word (Report)

Streamlit Web App

Jupyter / Python scripts

🚀 How to Run the Dashboard
1. Install Dependencies
pip install streamlit pandas numpy seaborn matplotlib

2. Run the Streamlit App
streamlit run app.py


The dashboard will open in your browser.

🏁 Summary

This People Analytics project delivers:

A complete E2E HR analytics workflow

A dynamic Streamlit dashboard

Deep insights into attrition & workforce patterns

Recommendations backed by data & visualizations
