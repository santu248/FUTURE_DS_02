# Task 2: Customer Retention & Churn Analysis

**Intern:** Santu Mondal  
**CIN ID:** FIT/OCT26/DS24105  
**Domain:** Data Science & Analytics  
**Tools Used:** Python (pandas), HTML/JS (Interactive Dashboard)

---

## 📌 Project 1: Telco Customer Churn Dataset (Kaggle) (1)

**Objective:** Analyze customer data to identify churn patterns, key retention drivers, and customer lifetime trends for a subscription-based business.

👉 **[Click here to view Project 1 Full Report (PDF)](Project_1_Churn_Report.pdf)**

### 🔍 Key Findings (Telco)
- **26.5%** overall churn rate.
- **High-Risk Groups:** Month-to-month contracts (43% churn), first-year tenure (47% churn), Fiber optic internet users, E-check payment method users, customers with no tech support, and senior citizens.

### 💡 Recommendations (Telco)
- Encourage customers to switch to longer-term contracts.
- Focus retention efforts on the first-year customer segment.
- Provide targeted tech support and onboarding for Fiber optic and E-check users.

---

## 📌 Project 2: SaaS Subscription Churn Dataset (Kaggle) (2)

**Objective:** Analyze the SaaS (RavenStack) dataset to understand account churn, MRR loss, and the impact of acquisition channels, industry, and trial conversions.

👉 **[Click here to view Project 2 Full Report (PDF)](churn_retention_dashboard)**  
👉 **[Click here to view the Python Analysis Code](analysis)**

### 📊 Executive Summary (SaaS)
- **22.0%** of 500 accounts churned.
- Churned accounts held **$2,355,245** of $11,338,747 cumulative subscription MRR (**-21%**).
- **Biggest Levers:** Acquisition channel, industry, and trial conversion.

### 🔍 Key Findings (SaaS)
- **Churn by Industry:** DevTools has the highest churn at **31.0%**, followed by FinTech (22.3%) and HealthTech (21.9%).
- **Churn by Referral Source:** Event-sourced accounts churn at **30.2%**, while partner-referred accounts churn the least (14.6%).
- **Churn by Country:** Germany (DE) shows the highest churn at **32.0%**.
- **Trial Accounts:** Trial accounts churn significantly more (**26%**) compared to non-trial (21%).
- **Cohort Retention:** Newer cohorts retain better (71% for 2023Q1 to 85% for 2024Q4), though recent cohorts have had less time to churn.

### 💡 Recommendations (SaaS)
- Shift marketing spend to partner/organic channels and review DevTools product fit.
- Improve trial-to-paid onboarding to reduce the 26% trial churn.
- Prioritize product gaps (specifically "features", which is the top stated churn reason).
- Note: Plan tier and support metrics do not separate churners, so pricing tier is not the main driver.

---

## 📁 Repository Files
- `Project_1_Churn_Report.pdf` - Project 1 (Telco) Report
- `Project_2_SaaS_Churn_Report.pdf` - Project 2 (SaaS) Report
- `churn_analysis_code.pdf` - Python analysis script for both datasets
- `dashboard.html` - Interactive retention dashboard (if uploaded)

---
*This project was completed as part of the Data Science & Analytics Internship at Future Interns.*
