# 🚀 DigitalPay Analytics  
## End-to-End Payment Transaction Intelligence & Failure Risk Dashboard  

---

## 📌 Project Overview

DigitalPay Analytics is an end-to-end data analytics project designed to simulate, analyze, and visualize digital payment transaction performance.

Since real-world digital transaction datasets are confidential and not publicly available, synthetic transaction data was generated to replicate realistic banking and payment behavior including:

- Success vs Failure patterns  
- Network-type impact (2G / 3G / 4G / 5G / WiFi)  
- Payment method performance (UPI, Debit Card, Credit Card, Wallet, Net Banking)  
- Seasonal and peak-hour risk trends  
- Failure reason diagnostics  

This project follows the complete analytics lifecycle:

> Data Generation → Data Cleaning → EDA → Feature Engineering → BI Modeling → Executive Dashboard → Business Insights

---

# 🎯 Business Problem

High transaction volume does not automatically translate into platform reliability.

Digital payment systems face:

- High failure rates during peak hours  
- Network-related performance issues  
- Authentication and bank server failures  
- Seasonal stress spikes  
- Revenue loss due to dropped transactions  

The goal of this project is to:

✔ Identify key transaction failure drivers  
✔ Analyze payment method reliability  
✔ Detect seasonal and peak-time risks  
✔ Provide actionable business recommendations  

---

# 🛠️ Tech Stack

| Layer | Tools Used |
|-------|------------|
| Data Simulation | Python |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Data Cleaning | Jupyter Notebook |
| Business Intelligence | Power BI |
| Data Modeling | DAX |
| Version Control | Git & GitHub |

---

# 📂 Project Workflow

## 1️⃣ Synthetic Data Generation

- Generated realistic digital transaction dataset
- Simulated fields:
  - Transaction Date
  - Payment Method
  - Network Type
  - Bank Name
  - Device Type
  - Transaction Amount
  - Transaction Status (Success / Failed / Dropped)
  - Failure Reason

---

## 2️⃣ Data Cleaning & Preprocessing (Python)

Performed inside Jupyter Notebook:

- Handling missing values  
- Removing duplicates  
- Data type corrections  
- Feature engineering  
- Extracted:
  - Month
  - Day Name
  - Hour
  - Derived metrics  

Notebook File:
```
Solution_digital_payment_transactions.ipynb
```

---

## 3️⃣ Exploratory Data Analysis (EDA)

Analyzed:

- Monthly transaction trends  
- Failure rate distribution  
- Payment method success comparison  
- Network-type performance  
- Peak hour stress analysis  
- Weekend vs weekday impact  

---

## 4️⃣ Power BI Data Modeling

After cleaning, data was imported into Power BI.

Created DAX measures:

- Total Transactions  
- Total Transaction Amount  
- Success Rate %  
- Failure Rate %  
- Average Transaction Value  
- Failed Transactions  

Added interactive slicers:

- Date Filter  
- Bank Name  
- Device Type  
- Network Type  
- Payment Method  

---

# 📊 Dashboard Pages

---

## 1️⃣ Transaction Overview

Includes:

- KPI Cards (Total Transactions, Success %, Failure %, Avg Value)
- Monthly Failure Rate Trend
- Success vs Failure vs Dropped Distribution
- Executive Insight Summary

Key Insight:
~58% success rate indicates execution inefficiency rather than volume issues.

---

## 2️⃣ Payment Method Performance

- Success Rate vs Volume Analysis
- Success Rate % by Payment Method
- Failed Transactions by Payment Method
- Network-wise Failure Trends

Key Insight:
UPI drives the highest volume and absolute failures due to scale, while Wallet shows more stability.

---

## 3️⃣ Failure Reason Analysis

- Failure Breakdown by Reason
- Failed Transactions by Network Type
- Payment Method vs Failure Reason Matrix

Major Failure Drivers:

- Insufficient Balance  
- Network Timeout  
- Authentication Failure  

---

## 4️⃣ Time & Peak Analysis

- Failure Rate by Month
- Failed Transactions by Day
- Failure Rate by Hour
- Weekend vs Weekday Comparison

Observations:

- Mid-year and December show seasonal spikes  
- Evening hours show higher failure rates  
- Weekends record increased transaction stress  

---

## 📈 Key Insights

- Over 40% of transactions either fail or drop
- Network and authentication issues dominate system-level risks
- Peak hours significantly impact reliability
- Volume alone does not define performance efficiency

---

## 💼 Business Recommendations

- Optimize UPI infrastructure during peak hours  
- Strengthen authentication and network-handling mechanisms  
- Implement predictive monitoring for peak-hour failures  
- Prioritize reliability improvements during seasonal spikes  

---

## 🔮 Future Scope

- Build ML-based failure prediction model  
- Deploy real-time monitoring dashboard  
- Integrate anomaly detection  
- Add SLA-based bank performance evaluation  
- Implement cloud-based scaling simulation  

---

# 📁 Repository Structure

```
DigitalPay-Analytics/
│
├── data/
│   ├── digital_payment_transactions_dataset.csv
│   ├── cleaned_digital_payment_transactions.csv
│
├── notebooks/
│   └── Solution_digital_payment_transactions.ipynb
│
├── dashboard/
│   └── DigitalPay_Analytics.pbix
│
├── images/
│   └── dashboard_snips.png
│
└── README.md
```
# 📊 Dashboard:
<img width="1307" height="723" alt="image" src="https://github.com/user-attachments/assets/7c01ec81-571d-420b-ad81-922ff0d7b1b0" />
---
<img width="1226" height="698" alt="image" src="https://github.com/user-attachments/assets/985ecb63-a3a0-40bf-8e65-9cad4bd269d0" />
---
<img width="1223" height="695" alt="image" src="https://github.com/user-attachments/assets/934e634d-d27b-477e-a26c-a9ef216b476d" />
---
<img width="1224" height="692" alt="image" src="https://github.com/user-attachments/assets/96d1f3c8-e459-4f1f-aafb-c5ac316a86e0" />
---
<img width="1233" height="695" alt="image" src="https://github.com/user-attachments/assets/2252e073-6e73-4eda-bf1f-12198a99c65f" />
---

---

If you found this project insightful, consider giving it a ⭐ on GitHub.
