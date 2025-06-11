

# 🍽️ Restaurant KPI Tracker – The Beach Bar & Grill

## 📊 Project Summary

This project analyses the operational performance of *The Beach Bar & Grill*, a high-traffic beachside restaurant, using simulated data structured in a SQL database. The objective is to help restaurant management make smarter, data-driven decisions about staffing, cost control, and profit optimisation by tracking labour costs, shift profitability, and order trends.

---

## 🚨 Business Problems Addressed

1. **Lack of visibility into profit per shift**
2. **Labor cost inefficiencies**
3. **Confusion between busy and profitable hours**
4. **Inconsistent role distribution (FOH & Kitchen)**
5. **Unclear menu item profitability**

---

## 🎯 Project Goals

- Build a SQL-powered restaurant data model using:
  - POS Orders
  - Kitchen & FOH rosters
  - Menu-level cost and prep info

- Create SQL queries to:
  - Tag shifts
  - Calculate labour cost per role and shift
  - Track profit per shift
  - Compare order volume to net profit by hour

- Visualise results in Power BI

---

## 🗂️ Datasets Included

| Table Name         | Description                                 |
|--------------------|---------------------------------------------|
| `menu_items`       | Menu name, category, price, cost, prep time |
| `pos_orders`       | Timestamped order data, item sold, server   |
| `kitchen_roster`   | Chef and kitchen hand shifts with pay info  |
| `foh_roster`       | FOH shifts: bar, cashier, pass, runner      |

---

## 🛠️ Technologies Used

- **Python** – Data simulation
- **SQLite / PostgreSQL** – SQL-based analysis layer
- **SQL** – Business logic, KPIs, and time tagging
- **Power BI** – Final dashboard & insights
- **Excel / CSV** – Optional validation layer

---

## 📈 Key Metrics

- **Shift Profit** = Revenue – Labor – COGS
- **Labor/Sales Ratio**
- **Revenue per Staff Hour**
- **Profit by Hour**
- **Busy vs. Profitable Shifts**

---

## 📌 Project Workflow

1. Load CSVs into SQL database
2. Use SQL to tag shifts, calculate metrics, and join datasets
3. Export summary tables for the Power BI dashboard
4. Analyse trends and build actionable insights

---

## 👨‍🍳 Built by Matheus Hilario – Data Analyst & Chef

