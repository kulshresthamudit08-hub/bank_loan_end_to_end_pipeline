# 🏦 Bank / Credit Risk Analysis - End to End Pipeline

Complete Credit Risk analytics pipeline: Excel → SQL → Python (EDA + ML) → Power BI with RLS.

# Business Objective
To analyze loan default risk and build a risk scoring system to identify high-risk borrowers based on demographics, credit history, and loan intent.

# Project Structure 

#1.Excel for Business Analysis
- `Business_Insights_Scenario` - What-if analysis for business decisions
- `GOAL_SEEK` - Goal seek for target recovery / profit
- `Pivot1`, `Pivot2` - Pivot tables for loan purpose, default analysis

# 2.SQL Queries (MySQL)
- Data Quality: `null_check`, `duplicate_check`
- KPI & Business: `KPI_Query`, `total_default`, `TOP_Risk_Factor`
- Segmented Risk Analysis: `education_default`, `gender_default`, `home_ownership_default`, `loan_intent_default`
- Advanced Analysis: `Conditional_query_AGE_Analysis`, `Window_Function_Risk_analysis

#3. Python- EDA + ML Model
- EDA
- Data Cleaning: `null_checking`, `duplicate_check`, `outlier_detection`, `2outlier_detection`, `outlier_removal`
- Visualization: heatmap,confusion matrix
- ML Model - Random Forest

# 4.Power BI Dashboard
- `Bank_Overview` - Overall portfolio KPI view
- `Risk_Analysis` - Deep dive into defaulters
- `ML_Model_Result` - Model performance in BI
- `RLS` & `after_RLS` - Row Level Security implementation
- `Summary_insights` & `BI BANK RISK ANALYSIS` PDF - Final business insights

# Key Insights
- Education, Home Ownership & Loan Intent are top risk factors
- Credit Score & Age segments show distinct default patterns
- Random Forest model helps predict potential defaulters
- RLS implemented for secure region/manager wise access

#Tools Used
Excel (Scenario, Goal Seek, Pivot) | MySQL (Window Functions, Rank, Row Number) | Python (Pandas, Seaborn, Sklearn) | Power BI (RLS, DAX)

---
Author: Mudit Kulshrestha | Data Analyst
**GitHub:** kulshresthamudit08-hub
