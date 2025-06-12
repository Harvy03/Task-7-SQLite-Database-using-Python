# 🧾 Task 7: Basic Sales Summary using SQLite and Python

## 📌 Objective
Build a simple data analysis script that:
- Connects to a tiny SQLite database
- Runs basic SQL queries to summarize sales data
- Displays results using `print()` and a basic bar chart with `matplotlib`

---

## 🛠️ Tools Used
- Python
- SQLite (via `sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook / Python Script (.py)

---

## 🗃️ Dataset
A self-created SQLite database file named `sales_data.db` with one table: `sales`.

### Table Structure:
| Column   | Type    | Description             |
|----------|---------|-------------------------|
| product  | TEXT    | Name of the product     |
| quantity | INTEGER | Units sold              |
| price    | REAL    | Price per unit          |

---

## 🚀 Features
- Creates and connects to a SQLite database
- Inserts sample sales data into the `sales` table
- Runs a SQL query to calculate:
  - Total quantity sold per product
  - Total revenue (quantity × price)
- Displays the summary using:
  - Pandas DataFrame
  - Matplotlib bar chart
- Saves the chart as `sales_chart.png`

---

## 📊Output

### Printed Summary (via `print(df)`):
product total_qty revenue
0 Apple 30 150.0
1 Banana 15 45.0
2 Orange 12 48.0


### Bar Chart:
A simple bar chart displaying revenue per product.
![image](https://github.com/user-attachments/assets/b7d46358-dca8-481a-bf8a-1d3a4418cd0e)

---

## 📁 Files Included
- `Task 7 SQLite Database using Python.ipynb`: Main script/notebook
- `sales_data.db`: SQLite database file 
- `sales_chart.png`: Output chart (auto-generated)
- `README.md`: Project documentation

---
