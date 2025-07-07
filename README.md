# 📊 Customer Churn Behavior Dashboard

This project analyzes customer churn behavior using simulated transactional and demographic data. The goal is to identify **which users are more likely to churn** and **what features are correlated with churn behavior**, using Python for analysis and Tableau for visualization.

---

## 🔍 Objective

To answer the question: **Why do users churn?**

We explored behavioral patterns across age, gender, and feature usage (QRIS, top-up, transfer, voucher).

---

## 📁 Project Structure

| File                     | Description                                           |
|--------------------------|-------------------------------------------------------|
| `Correlation Analysis.ipynb` | Python notebook for correlation and data merging    |
| `correlation_analysis.csv`   | Output of correlation scores between features and churn |
| `transactions.csv`      | Transaction history of users                          |
| `usage.csv`             | Usage behavior (QRIS, top-up, transfer, voucher)      |
| `users.csv`             | Demographic data including age and gender             |
| `Churn Analysis.twb`    | Tableau workbook                                      |
| `Dashboard Screenshot.png` | Static image of the Tableau dashboard                |

---

## 📈 Dashboard Overview

🔗 **View the full dashboard here**:  
[👉 Tableau Public Dashboard](https://public.tableau.com/app/profile/faza.firjatullah.alvi/viz/UserChurnAnalysisDashboardSimulatedTelcoData/Dashboard1?publish=yes)

---

## 💡 Key Insights

### 🧠 Churn Rate
- **Only 7.8%** of users churn — a small but crucial segment.

### 👥 Demographics
- 📊 **Age 26–35** has the **highest churn** rate (33.3%)
- 👩‍💼 **Female users** account for 66.7% of churn

### ⚙️ Feature Usage vs Churn Correlation

| Feature         | Correlation |
|----------------|-------------|
| `used_qris`     | +0.089      |
| `used_topup`    | **–0.054**  |
| `used_transfer` | +0.012      |
| `used_voucher`  | +0.092      |

🧾 **Interpretation**:
- **Vouchers and QRIS** show weak **positive correlation** → promo-based users may churn more  
- **Top-up** shows **negative correlation** → frequent top-up users appear more loyal

---

## ✅ Call to Action

- 🎯 Focus retention strategies on **users aged 26–35**, especially **female users**
- 💡 Reduce reliance on promotions to **encourage long-term engagement**

---

## ⚙️ Tools Used

- **Python (Pandas, Seaborn)** for data cleaning and analysis  
- **Tableau Public** for visualization  
- **Jupyter Notebook**  
- **GitHub** for version control

---

## 📝 License

This project uses **simulated data** for educational and portfolio purposes.
