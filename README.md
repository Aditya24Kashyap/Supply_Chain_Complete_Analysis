# 📦 Supply Chain Analysis & Delay Prediction

## 🚀 Project Overview
This project analyzes a real-world supply chain dataset to identify delivery inefficiencies, detect bottlenecks, and predict late deliveries using machine learning.

It demonstrates how data analysts solve business problems using **data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling**.

---

## 🎯 Business Problem
Late deliveries impact:
- Customer satisfaction
- Operational efficiency
- Profitability

### Key Questions:
- Why are deliveries getting delayed?
- Which factors contribute most to delays?
- How do delays affect profit?
- Can we predict late deliveries?

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
- Customer data
- Product information
- Profit & sales metrics

---

## 🔄 Project Workflow

### 1. Data Cleaning
- Removed irrelevant and high-missing columns
- Dropped sensitive fields (email, password, etc.)
- Converted date columns to datetime
- Removed canceled orders

---

### 2. Feature Engineering
Created new features:
- `Order Processing Time`
- `Delay`
- `Is_Delayed` (Target Variable)
- `order_month`, `order_day`, `order_hour`
- `Profitability Flag` (Profit / Loss / Break-even)

---

### 3. Exploratory Data Analysis (EDA)

#### Key Insights:
- 📊 **54.7% orders are delayed**
- 💰 Total Profit: **~7.5M $**
- ⚠️ Loss due to delays: **~2.1M $**

---

### 4. Delay Analysis
- Most common delay: **1 day (~31%)**
- Maximum delay observed: **4 days**
- Increasing delay → decreasing profitability

---

### 5. Bottleneck Detection
Analyzed delays across:
- Shipping Mode
- Customer Segment
- Order Status
- Department
- Region

📌 Example:
- **Home Office segment has highest delay (~55%)**

---

### 6. Root Cause Analysis
Top delay drivers:
- Shipping mode inefficiencies
- Order processing status
- Regional logistics issues

---

### 7. Time-Based Analysis
- 📅 Highest delays: **Aug–Sep**
- 📆 Weekday patterns observed
- 🕒 Order time affects delivery delays

---

### 8. Profitability Analysis
- ✅ 80.6% orders are profitable
- ❌ 18.7% orders result in loss
- Delayed orders significantly increase losses

---

### 9. Machine Learning Model
Built a classification model to predict:
- **Late Delivery Risk**

**Target Variable:** `Is_Delayed`

#### Outcome:
- Helps identify high-risk orders
- Enables proactive decision-making

---

## 📊 Key Business Insights
- 🚚 Over **50% deliveries are delayed**
- 💸 Delays cause significant financial loss
- 📦 Shipping mode is a major bottleneck
- 🌍 Certain regions consistently underperform
- ⏱ Even small delays impact profitability

---

## 💡 Recommendations
- Optimize shipping methods
- Improve order processing workflows
- Prioritize high-value delayed orders
- Use ML model for early risk detection
- Plan logistics based on seasonal trends

---

## 📈 Future Improvements
- Deploy model using Flask / FastAPI
- Build dashboard using Power BI / Tableau
- Implement real-time prediction system
- Use advanced ML models (XGBoost, LightGBM)

---

## 📊 Visualizations
- Delay distribution
- Profit vs Delay analysis
- Bottleneck detection charts
- Time-based trends

---

## 🧠 Learnings
- End-to-end data analytics workflow
- Business problem solving using data
- Feature engineering techniques
- Turning insights into actionable decisions

---

## 🤝 Connect
If you found this project helpful, feel free to connect or give a ⭐ to the repo!

---
