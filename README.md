# Customer-Retention-for-an-Online-Subscription-Platform
Optimizing Customer Retention for an Online Subscription Platform

Goal: discover why users churn, segment users by value & risk, propose interventions and run a prioritized retention roadmap.
Business outcomes you’ll deliver: cohort retention dashboard, LTV & CAC estimates, churn-prediction model, prioritized retention initiatives with estimated MRR impact and an A/B test plan.

# 📊 Telco Customer Churn Analysis – Power BI Project

### 🧠 Objective

Analyze customer churn behavior to identify key drivers of attrition and provide data-driven recommendations for customer retention.

---

### 🧱 Dataset

* **Source:** Telco Customer Churn dataset (Kaggle)
* **Rows:** 7,043 customers
* **Fields:** Demographics, subscription details, charges, and churn status

---

### 🧰 Tools & Technologies

* **Power BI** – Dashboard creation & insights visualization
* **Python (pandas, matplotlib, seaborn)** – Data cleaning, churn modeling & cohort analysis
* **GitHub** – Version control and portfolio presentation

---

### ⚙️ Process Overview

1. **Data Cleaning (Python)**

   * Converted `TotalCharges` to numeric and handled missing values
   * Created derived features such as `StartMonth` and `CohortMonth`
   * Removed zero-tenure records and standardized churn labels

2. **Cohort Analysis**

   * Measured customer retention over tenure
   * Visualized cohort-wise retention using heatmaps

3. **Churn Prediction Model**

   * Built logistic regression model
   * Achieved **ROC-AUC = 0.84**
   * Key predictive features: `tenure`, `PhoneService`, `Contract`, `MonthlyCharges`, `TotalCharges`

4. **Power BI Dashboarding**

   * Designed two-page dashboard for storytelling:

     * **Executive Summary** – KPIs, churn rate, revenue loss, and key visuals
     * **Demographics & Behaviour** – Gender, dependents, tenure, and payment analysis
   * Applied consistent theme, rounded cards, drop shadows, and highlight colors

---

### 📈 Key Insights

* Overall churn rate: **26.5%**
* Highest churn among **Month-to-Month** and **Electronic Check** users
* Customers with **tenure < 6 months** show **maximum churn risk**
* **Automatic payments** and **long-term contracts** reduce churn significantly

---

### 🖼️ Dashboard Overview

#### 1️⃣ Executive Summary

<img width="2007" height="1132" alt="Screenshot 2025-11-05 170837" src="https://github.com/user-attachments/assets/cf2d4435-916d-48d9-b346-d950183a3e2b" />


#### 2️⃣ Demographics & Behaviour

<img width="2004" height="1125" alt="Screenshot 2025-11-05 170854" src="https://github.com/user-attachments/assets/360b7415-ac21-42e0-926a-bd3eab752e61" />


---

### 🧩 Business Impact

* Identified high-risk customer segments for proactive retention
* Recommended tenure-based loyalty interventions
* Demonstrated practical BI storytelling aligned with business KPIs

---

### ✍️ Author

**Sahil Rajan Tiwatne**
*Business Analyst | Power BI | Python | Data-Driven Decision Making*

