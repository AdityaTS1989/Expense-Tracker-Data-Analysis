# 💸 Expense Tracker — Personal Finance Analytics

A data science project that simulates, analyzes, and visualizes personal expense data across a full year. Mimics real FinTech use cases used by platforms like CRED, Paytm, and Google Pay.

---

## 📊 Project Overview

| Item | Details |
|---|---|
| Dataset | Synthetic — 698 transactions, 8 categories, 5 payment modes |
| Period | January 2024 – December 2024 |
| Monthly Avg Spend | ₹31,945 |
| Avg Savings Rate | 29% |
| Libraries | pandas, numpy, matplotlib, seaborn |

---

## 🔍 What This Project Does

- Generates realistic expense data across food, rent, transport, shopping, health, education
- Analyzes monthly trends and weekday vs weekend patterns
- Compares actual spend vs monthly budget per category
- Detects over-budget categories automatically
- Calculates monthly savings rate against assumed income

---

## 📈 Key Findings

- Top spending category: **Shopping**
- Top payment method: **UPI**
- Average savings rate: **29% per month**

---

## 📈 Output Charts

### Main Analytics Dashboard
![Dashboard](chart1_main_dashboard.png)

### Monthly Category Heatmap
![Heatmap](chart2_monthly_heatmap.png)

### Budget vs Actual
![Budget](chart3_budget_vs_actual.png)

### Top 10 Transactions + Weekly Trend
![Top10](chart4_top10_weekly.png)

### Quarterly + Savings Rate
![Savings](chart5_quarterly_savings.png)

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn
```

Open `Expense_Tracker_App.ipynb` in Jupyter Notebook and run all cells.

---

## 📁 Project Files

| File | Description |
|---|---|
| `Expense_Tracker_App.ipynb` | Main notebook |
| `expense_data.csv` | 698-transaction dataset |
| `chart1_main_dashboard.png` | Full analytics dashboard |
| `chart2_monthly_heatmap.png` | Monthly heatmap |
| `chart3_budget_vs_actual.png` | Budget health check |
| `chart4_top10_weekly.png` | Top transactions + weekly trend |
| `chart5_quarterly_savings.png` | Savings rate analysis |
