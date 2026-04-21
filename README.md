# 📦 Supply Chain Analysis & Delivery Delay Prediction

## 🚀 Project Overview
This project analyzes a real-world supply chain dataset to identify **delivery delays, operational bottlenecks, and profitability impact**, and builds a **machine learning model** to predict late deliveries.

It simulates a real business scenario where data is used to improve logistics and decision-making.

---

## 🎯 Business Problem
Late deliveries negatively affect:
- Customer satisfaction  
- Operational efficiency  
- Revenue and profitability  

### Key Questions:
- Why are deliveries getting delayed?
- Which factors contribute most to delays?
- How do delays affect profit?
- Can we predict late deliveries in advance?

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 📂 Dataset
- **180,000+ rows**
- **50+ features**

Includes:
- Order details  
- Shipping timelines  
- Customer segments  
- Product categories  
- Profit & sales metrics  

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Removed irrelevant & high-missing columns  
- Dropped sensitive data (email, password, etc.)  
- Converted date columns to datetime  
- Removed canceled orders  

---

### 2️⃣ Feature Engineering
Created new features:
- `Order Processing Time`
- `Delay`
- `Is_Delayed` (Target Variable)
- `order_month`, `order_day`, `order_hour`
- `Profitability Flag` (Profit / Loss / Break-even)

---

## 📊 Exploratory Data Analysis

### 🔹 Profitability Distribution
![Profitability](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/profitability%20pie.png)


- ✅ 80.6% orders are profitable  
- ❌ 18.7% orders result in loss  

---

### 🔹 Delay Distribution
![Delay Distribution](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/delay%20distribution.png)

- 📊 54.7% orders are delayed  
- Most common delay: **1 day (~31%)**

---

### 🔹 Profit vs Delay Analysis
![Profit vs Delay](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/profit%20vs%20delay.png)

- 📉 Profit decreases as delay increases  
- Delays significantly impact revenue  

---

## 🚧 Bottleneck Detection
![Bottleneck Analysis](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/bottleneck%20analysis.png)

Analyzed delays across:
- Shipping Mode  
- Customer Segment  
- Order Status  
- Department  
- Region  

📌 **Key Insight:**  
- Home Office segment shows highest delay rate (~55%)

---

## 🔍 Root Cause Analysis
![Root Cause Analysis](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/root%20cause.png)

Top drivers of delay:
- Inefficient shipping modes  
- Order status issues (Pending / Processing)  
- Regional logistics inefficiencies  

---

## ⏱ Time-Based Analysis
![Time Analysis](https://raw.githubusercontent.com/Aditya24Kashyap/Supply_Chain_Complete_Analysis/main/time%20analysis.png)

- 📅 Peak delays in **Aug–Sep**  
- 📆 Certain weekdays show higher delays  
- 🕒 Order hour impacts delivery performance  

---

## 🤖 Machine Learning Model

### Objective:
Predict **Late Delivery Risk**

- Target Variable: `Is_Delayed`  
- Model Type: Classification  

### Outcome:
- Identifies high-risk orders  
- Enables proactive logistics decisions  

---

## 📈 Key Business Insights
- 🚚 **54.7% deliveries are delayed**
- 💸 ~**2.1M $ loss due to delays**
- 📦 Shipping mode is a major bottleneck  
- 🌍 Regional inefficiencies exist  
- ⏱ Even small delays reduce profit  

---

## 💡 Recommendations
- Optimize shipping strategies  
- Improve order processing workflows  
- Prioritize high-value delayed orders  
- Use ML model for early risk detection  
- Plan logistics for peak seasons  

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

### Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the notebook
```bash
jupyter notebook
```

---

## 🧠 Learnings
- End-to-end data analysis workflow  
- Real-world business problem solving  
- Feature engineering techniques  
- Converting insights into business decisions  

---

## ⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub!
