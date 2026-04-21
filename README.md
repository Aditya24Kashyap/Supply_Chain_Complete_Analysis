# 📦 Supply Chain Optimization & Delivery Risk Prediction

## 🏢 Business Context
In modern e-commerce operations, supply chain efficiency is critical to maintaining customer satisfaction and profitability. Delays in order fulfillment can lead to increased costs, customer churn, and operational inefficiencies.

This project simulates a real-world scenario where a company is experiencing high delivery delays and needs data-driven insights to optimize its logistics operations.

---

## 🎯 Problem Statement

A large-scale supply chain system is facing a high rate of delayed deliveries, impacting both customer experience and financial performance.

Analysis of historical order data reveals:
- 🚚 Over **54% of deliveries are delayed**
- 💸 Approximately **$2.1M loss associated with delayed orders**
- 📦 Delay patterns vary across shipping modes, customer segments, and regions

### Business Objectives:
- Identify key drivers of delivery delays  
- Quantify the impact of delays on profitability  
- Detect bottlenecks in the supply chain  
- Build a predictive model to identify high-risk deliveries  

---

## 🛠️ Solution Approach

A structured data analytics workflow was applied:

1. **Data Cleaning & Preparation**
2. **Feature Engineering**
3. **Exploratory Data Analysis (EDA)**
4. **Bottleneck Detection**
5. **Root Cause Analysis**
6. **Time-Based Trend Analysis**
7. **Machine Learning Modeling**

---

## 📂 Dataset Overview
- **180,000+ records**
- **50+ features**

Includes:
- Order and shipping details  
- Customer segmentation  
- Product categories  
- Sales and profit metrics  

---

## ⚙️ Feature Engineering

Key features created:
- `Order Processing Time`
- `Delay`
- `Is_Delayed` (Target Variable)
- Time-based features (Month, Day, Hour)
- `Profitability Flag`

These features help translate raw data into actionable business signals.

---

## 📊 Key Analysis & Insights

### 🔹 Profitability Distribution
![Profitability](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/profitability%20pie.png)

- 80.6% orders are profitable  
- 18.7% result in losses  
- Losses are strongly linked to delayed deliveries  

---

### 🔹 Delay Distribution
![Delay Distribution](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/delay%20distribution.png)

- 54.7% of orders are delayed  
- Most common delay: **1 day (~31%)**

---

### 🔹 Profit vs Delay Impact
![Profit vs Delay](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/profit%20vs%20delay.png)

- Profit decreases as delay increases  
- Even small delays negatively affect margins  

---

## 🚧 Bottleneck Identification
![Bottleneck Analysis](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/bottleneck%20analysis.png)

### Key Findings:
- Certain **shipping modes** show higher delay rates  
- **Home Office segment** has highest delay (~55%)  
- Order status (Pending / Processing) contributes significantly  

---

## 🔍 Root Cause Analysis
![Root Cause](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/root%20cause.png)

Top delay drivers:
- Inefficient shipping methods  
- Operational delays in order processing  
- Regional logistics constraints  

---

## ⏱ Time-Based Trends
![Time Analysis](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/time%20analysis.png)

- Peak delays observed in **Aug–Sep**  
- Weekly and hourly patterns impact delivery performance  
- Indicates demand-supply imbalance during peak periods  

---

## 🤖 Predictive Modeling

### Objective:
Predict **Late Delivery Risk**

- Target Variable: `Is_Delayed`
- Approach: Classification using Scikit-learn

### Business Value:
- Early identification of high-risk orders  
- Enables proactive logistics planning  
- Reduces delays and associated losses  

---

## 📈 Business Impact

- 🚚 High delay rate identified (**54.7%**)  
- 💸 Significant financial loss (~**$2.1M**)  
- 📦 Shipping mode and order status are critical factors  
- 🌍 Regional inefficiencies detected  

---

## 💡 Strategic Recommendations

- Optimize high-risk shipping modes  
- Improve order processing pipelines  
- Prioritize orders with high delay probability  
- Allocate resources during peak months  
- Use predictive model for real-time decision making  

---

## 📁 Project Structure
```
Supply-Chain-Analysis/
│
├── README.md
├── supply_chain_analysis.ipynb
├── DataCoSupplyChainDataset.csv
└── images/
    ├── profitability_pie.png
    ├── delay_distribution.png
    ├── profit_vs_delay.png
    ├── bottleneck_analysis.png
    ├── root_cause.png
    └── time_analysis.png
```

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

---

## 🧠 Key Learnings
- End-to-end business data analysis workflow  
- Translating data into business insights  
- Identifying operational inefficiencies  
- Building predictive models for decision support  

---

## ⭐ Conclusion
This project demonstrates how data can be leveraged to **optimize supply chain performance, reduce delays, and improve profitability** through actionable insights and predictive analytics.

---
