# ☕ Coffee Shop SQL Project

This project showcases a SQL-based analytical solution to evaluate the **Monthly Performance of a Coffee Shop**. Using PostgreSQL queries, it calculates trends in **sales, orders, and quantity sold**, along with their **month-over-month comparisons**. The project demonstrates how SQL can be effectively used for business intelligence and performance tracking.

---

## 📊 Objectives

This project answers the following business questions:

### 🟦 A. Sales Analysis
| View | Description |
|------|-------------|
| A    | Monthly Total Sales |
| B    | Month-over-Month % Change in Sales |
| C    | Difference in Sales from Previous Month |

### 🟩 B. Order Analysis
| View | Description |
|------|-------------|
| D    | Monthly Total Orders |
| E    | Month-over-Month % Change in Orders |
| F    | Difference in Orders from Previous Month |

### 🟨 C. Quantity Analysis
| View | Description |
|------|-------------|
| G    | Monthly Total Quantity Sold |
| H    | Month-over-Month % Change in Quantity |
| I    | Difference in Quantity from Previous Month |

---

## 🛠️ Technologies Used

- **PostgreSQL**
- SQL concepts used:
  - `CREATE VIEW`
  - `SUM()`, `COUNT()`, `LAG()`, `ROUND()`
  - `TO_CHAR()`, `DATE_PART()`, `DATE_TRUNC()`
  - `NULLIF()` for safe division
  - Window functions for month-over-month comparisons

---

## 💡 Key Features

- 📈 **Track Monthly Sales Trends**
- 📦 **Measure Total Orders and Growth Rate**
- 🧾 **Analyze Product Demand by Quantity Sold**
- 📉 **Monitor Performance Changes Month-over-Month**
- 🔍 **Easy-to-read Views for Fast Access**

---

## 🚀 How to Use This Project

1. Load `Transactions` table into a **PostgreSQL** database.
2. Run the provided **SQL `CREATE VIEW` statements** in order (Views A to I).
3. Use:
   ```sql
   SELECT * FROM A; -- or B, C, D...I

---

## 🔗 GitHub Repository Link
https://github.com/Analyst-Rajat333/Coffee-Shop-SQL-Project

---

## 👨‍💻 Author

**Rajat Saxena**  
📧 **Email**: [rajatsaxena950@gmail.com](mailto:rajatsaxena950@gmail.com)  
🔗 **GitHub**: [Analyst-Rajat333](https://github.com/Analyst-Rajat333)


