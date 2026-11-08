# Task 2: Customer Retention & Churn Analysis

**Intern:** Santu Mondal  
**CIN ID:** FIT/OCT26/DS24105  
**Domain:** Data Science & Analytics  
**Tools Used:** Python (pandas), HTML/JS (Interactive Dashboard)

---

## 📌 Project 1: Telco Customer Churn Dataset (Kaggle) (1)

**Objective:** Analyze customer data to identify churn patterns, key retention drivers, and customer lifetime trends for a subscription-based business.

👉 **[Click here to view Project 1 Interactive Dashboard (HTML)](dashboard.html)**  
👉 **[Click here to view Project 1 Full Report (PDF)](Project_1_Churn_Report.pdf)** *(ফাইল আপলোড করার পর নাম ঠিক করে নিও)*

### 📊 Datasets Used
- RavenStack synthetic SaaS (credit: River @ Rivalytics)
- Telco Customer Churn (Kaggle)

### 🔍 Key Findings & Churn Patterns
**SaaS Dataset:**
- **22%** account churn observed.
- DevTools, event-referred accounts, Germany, and trial accounts churn the most.
- Plan tier and support levels do not differ significantly in churn rates.
- *Note: RavenStack is synthetic - small gaps may be noise.*

**Telco Dataset:**
- **26.5%** overall churn rate.
- **High-Risk Groups:** Month-to-month contracts (43% churn), first-year tenure (47% churn), Fiber optic internet users, E-check payment method users, customers with no tech support, and senior citizens.

### 💡 Recommendations
- Encourage customers to switch to longer-term contracts (1-year or 2-year) to reduce month-to-month churn.
- Focus retention efforts on the first-year customer segment.
- Provide targeted tech support and onboarding for Fiber optic and E-check users.
- Offer loyalty incentives or discounts for senior citizens and trial accounts.

### 📁 Project 1 Repository Files
- `dashboard.html` - Interactive retention dashboard (open in browser)
- `analysis.py` - pandas analysis (churn, cohorts, segments, support, lifetime)
- `results.json` - Generated analysis results

---
*This project was completed as part of the Data Science & Analytics Internship at Future Interns.*
