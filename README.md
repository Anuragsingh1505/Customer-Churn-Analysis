# 📊 Customer Churn Analysis (EDA Project)

## 📌 Project Overview
This project focuses on analyzing customer churn behavior in a telecom company using Exploratory Data Analysis (EDA). The goal is to identify key factors influencing churn and provide actionable business insights.

The dataset contains **7,043 customers** with various features like demographics, services, contract type, and payment methods.

---

## 🎯 Objective
- Identify patterns and trends behind customer churn
- Analyze key factors affecting retention
- Provide data-driven business recommendations

---

## 📊 Key Insights

- 📉 **Overall churn rate:** ~26.5% (1 in 4 customers churned)

### 👥 Demographics
- Gender has no significant impact on churn (~26–27%)
- Senior citizens have higher churn (~42%) vs non-seniors (~24%)

### ⏳ Tenure
- Majority of churn occurs in early-stage customers (0–12 months)
- Long-term customers (>24 months) have <15% churn

### 📜 Contract Type
- Month-to-month: ~45% churn
- 1-year contract: ~11% churn
- 2-year contract: ~3% churn

### 🧩 Services
- Customers without:
  - Tech Support (~40% churn)
  - Online Security (~42% churn)
- With services → churn drops to ~15–20%

### 🌐 Internet Service
- Fiber optic users: ~41% churn
- DSL users: ~19% churn

### 💳 Payment Method
- Electronic check users: ~45% churn (highest)
- Others: ~15–18% churn

---

## 📈 Tools & Technologies Used
- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📊 Visualizations
- Count plots
- Bar charts
- Pie charts
- Distribution plots
- Comparative analysis charts

---

## 🚀 Business Recommendations

- Improve onboarding for new customers (0–12 months)
- Promote long-term contracts (reduce churn from 45% → ~3%)
- Upsell value-added services (reduce churn by ~50%)
- Target high-risk segments (senior citizens, fiber users)
- Encourage better payment methods (reduce electronic check dependency)

---

## 🧾 Conclusion
Churn is driven by clear behavioral and service-based factors. By applying targeted strategies, churn can potentially be reduced from **26.5% to below 18%**, significantly improving retention.

---

## 📂 Project Structure
```
Customer-Churn-Analysis/
│── Customer churn.ipynb
│── dataset.csv
│── README.md
```

