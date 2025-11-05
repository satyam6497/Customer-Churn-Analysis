# 📊 Telecom Customer Churn Analysis

## 🧠 Project Overview  
This project explores customer churn data from a telecom company to uncover insights about customer retention and behavior. The analysis focuses on identifying the key factors driving churn such as contract type, tenure, payment methods, and monthly charges.  
An interactive dashboard is also developed to visualize major KPIs and trends.

---

## 🎯 Objectives
- Understand customer demographics and service usage patterns.  
- Identify major factors influencing customer churn.  
- Visualize key business insights with intuitive charts and dashboards.  
- Provide actionable recommendations to improve customer retention.

---

## 📁 Dataset  
**Source:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)  
**Rows:** 7043  
**Columns:** 21  
**Target Variable:** `Churn` (Yes/No)

Key columns include:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- `tenure`, `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`

---

## 🧩 Steps in the Analysis

1. **Data Cleaning & Preprocessing**
   - Handled missing values in `TotalCharges`
   - Converted categorical variables into numeric form
   - Standardized column names for readability

2. **Exploratory Data Analysis (EDA)**
   - Visualized customer churn distribution by multiple parameters  
   - Identified trends related to contract duration, tenure, and payment modes  
   - Generated correlation heatmap for numerical variables

3. **Dashboard Design**
   - Built a clean, minimal **Analyst Dashboard** (white background)  
   - Included filters for contract type and payment method  
   - Focused on simplicity and insight-driven visual storytelling  

---

## 📈 Key Visualizations

### 🔹 Churn by Contract Type
Customers with **month-to-month contracts** show significantly higher churn rates compared to long-term contracts.  
![Churn by Contract Type] <img width="774" height="619" alt="Screenshot 2025-11-05 085512" src="https://github.com/user-attachments/assets/e7ff2076-7a39-4ea6-a482-94ba1556227b" />


---

### 🔹 Churn by Tenure
Customers who have recently joined (short tenure) are more likely to churn, while long-term customers tend to stay.  
![Churn by Tenure] <img width="1803" height="568" alt="Screenshot 2025-11-05 085450" src="https://github.com/user-attachments/assets/1e99c4f0-e351-4c5f-8d5e-913296e9ea35" />


---

### 🔹 Churn by Payment Method
Electronic check users show the highest churn, suggesting possible dissatisfaction with billing or service.  
![Churn by Payment Method]( <img width="867" height="708" alt="Screenshot 2025-11-05 085636" src="https://github.com/user-attachments/assets/59fe017d-22f3-44e6-8dbb-8bd88dcd8b58" />


---

### 🔹 Correlation Heatmap
Displays relationships between numerical variables such as `MonthlyCharges`, `Tenure`, and `TotalCharges`.
![Correlation Heatmap]<img width="2705" height="1753" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/ab3f7c7c-ec41-44ca-a7a1-551cd1df41a0" />

---

## 🧠 Insights & Recommendations
- 📉 **Short Tenure = High Churn:** New customers are more likely to leave; implement onboarding offers.  
- 💳 **Electronic Check Users:** Consider incentivizing digital auto-pay methods.  
- 📅 **Long-term Contracts Retain Better:** Promote annual or bi-annual plans with discounts.  
- 💡 **Targeted Retention Campaigns:** Focus on high monthly charge customers with flexible offers.

---

## 🧰 Tools & Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Visualization:** Power BI / Excel  
- **Environment:** Jupyter Notebook  

---

## 👨‍💻 Author
**Satyam Mishra**  
Data Analyst | Business Intelligence Enthusiast  
📧*[satyam_mishra.dec17@gmail.com ]*
🔗[LinkedIn](https://www.linkedin.com/in/satyam-mishra-dec17/) | [GitHub](https://github.com/satyam6497/)



