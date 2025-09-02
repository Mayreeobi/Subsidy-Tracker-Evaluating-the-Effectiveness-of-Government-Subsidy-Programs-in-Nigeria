- # Subsidy Tracker – Evaluating the Effectiveness of Government Subsidy Programs in Nigeria 🇳🇬

## 📌 Introduction
Governments invest heavily in subsidy programs (fuel, food, and cash transfers) to reduce poverty and cushion vulnerable households. Despite the intent, issues such as **leakage, fraud, and poor targeting** hinder effectiveness.  

This project evaluates subsidy disbursement in **Nigeria**, measuring **coverage, targeting accuracy, leakage, and fraud detection**, while offering **data-driven recommendations** for policy and implementation improvement. - 

---

## 🔗 Python Code 
- [Code Here](https://github.com/Mayreeobi/Subsidy-Tracker-Evaluating-the-Effectiveness-of-Government-Subsidy-Programs-in-Nigeria/blob/main/Subsidy%20Disbursement%20in%20Nigeria.ipynb)

---

## 📂 Dataset Overview
- **Rows:** 80,025  
- **Columns:** 17  
- **Duplicates:** None  

### 🔑 Key Columns
- `National_ID`: Unique identifier for each beneficiary  
- `Age`: Age of beneficiary  
- `Gender`: Male/Female  
- `Region`: State/region where beneficiary resides  
- `Income_Level`: Low, Middle, High  
- `Household_Dependents`: Number of dependents  
- `Monthly_Energy_Consumption_kWh`: Estimated household energy usage  
- `Subsidy_Eligibility`: Whether beneficiary qualifies  
- `Subsidy_Type`: Fuel, Food, Cash transfer  
- `Amount_(NGN)`: Amount disbursed  
- `Channel`: Disbursement channel (Mobile Wallet, Bank, Cash)  
- `Date`: Date of disbursement  
- `Wallet_Activity_Status`: Active, Inactive, Suspicious  
- `Wallet_Balance_(NGN)`: Balance during disbursement  
- `Days_Since_Last_Transaction`: Wallet inactivity duration  
- `Avg_Monthly_Wallet_Balance`: Past average balance  
- `Suspected_Fraud`: Flag for suspected fraud  

---

## 🧹 Data Cleaning
- **Handled Missing Values**  
  - Affected columns: `Wallet_Activity_Status`, `Wallet_Balance_(NGN)`, `Days_Since_Last_Transaction`, `Avg_Monthly_Wallet_Balance` (53,337 missing).  
  - Replaced numeric columns with **0** and categorical with **"Unknown"**.  
- Removed invalid symbols (`,` and `#`) from numeric fields.  
- Standardized all column names to lowercase.  
- Confirmed no duplicates.  

---

## 📊 Exploratory Data Analysis (EDA) Insights
- **Coverage:** 100% of eligible households captured.  
- **Targeting Accuracy:** Only **60.98%** of subsidies reached the intended low-income group.  
- **Leakage Rate:** **39.02%** of disbursements went to middle/high-income beneficiaries.  
- **Top Leakage Regions:** Kano, Yobe, Rivers, Lagos, Oyo.  
- **Gender Distribution:** Female beneficiaries received slightly more (**₦161M**) than males (**₦159M**).  
- **Age Distribution:**  
  - 30–44 years: largest share (**₦95M**)  
  - 60+ years: least share (**₦60M**)  
- **Wallet Activity:**  
  - Active: 18,502  
  - Inactive: 5,491  
  - Suspicious: 2,695  
- **Disbursement Channels:**  
  - Mobile Wallets dominated, accounting for **₦107M** in subsidy disbursement.  

---

## 🚀 Recommendations
1. **Improve Targeting** – Enhance eligibility checks & cross-verify with external datasets (poverty maps, census).  
2. **Fraud Monitoring** – Implement anomaly detection for suspicious wallet behavior.  
3. **Regional Rebalancing** – Address high leakage in Kano, Yobe, Rivers, Lagos, Oyo.  
4. **Digital-First Approach** – Mobile wallets dominate; strengthen **KYC & security protocols**.  
5. **Model Development** – Build and deploy machine learning models for **fraud detection & prevention**.  

---

## ⚙️ Next Steps
- Develop **fraud detection models** (Random Forest, Isolation Forest, Clustering).  
- Integrate **dashboards** for policymakers to track subsidy flow, leakage, and fraud risks.  

---

## 🛠️ Tools & Tech
- **Python (Pandas, NumPy, Matplotlib, Seaborn)**  
- **Jupyter Notebook** – for analysis and visualization


---


## 📌 Acknowledgments
Special thanks to  **DataVerse Africa** for this opportunity and support throughout this project.  

---


