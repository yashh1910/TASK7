# 📊 Task 7: SQLite Sales Data Analysis

## 🧾 Objective
Analyze product sales data using an in-memory SQLite database and visualize monthly revenue by product category using Python, SQLite, and Matplotlib.

---

## 📁 Dataset Overview

| Column Name | Description                     |
|-------------|---------------------------------|
| product     | Name of the product             |
| category    | Product category (e.g., Electronics, Grocery) |
| quantity    | Quantity sold                   |
| price       | Price per unit                  |
| date        | Date of transaction (YYYY-MM-DD) |

---

## 🛠 Tools & Technologies
- Python 3
- SQLite (In-Memory)
- Pandas
- Matplotlib

---

## 📦 Sample Data

| Product  | Category    | Quantity | Unit Price | Date       |
|----------|-------------|----------|------------|------------|
| Laptop   | Electronics | 8        | 850.00     | 2025-01-03 |
| Milk     | Grocery     | 40       | 1.00       | 2025-01-10 |
| TV       | Electronics | 3        | 600.00     | 2025-02-11 |
| Bread    | Grocery     | 50       | 1.20       | 2025-02-20 |

---


## 🔍 Steps Performed

**Database Setup**  
- Created a table named `product_sales` using an SQLite in-memory database.

**Data Insertion**  
- Inserted sample records into the table.

**Querying**  
- Aggregated revenue and quantity by category and month.  
- Used `strftime('%Y-%m', date)` to group by month.

**Visualization**  
- Created a bar chart showing monthly revenue per category.

---

## 📊 Output Summary

| Category     | Month    | Total Quantity | Total Revenue |
|--------------|----------|----------------|----------------|
| Electronics  | 2025-01  | 8              | 6800.00        |
| Grocery      | 2025-01  | 40             | 40.00          |
| Electronics  | 2025-02  | 3              | 1800.00        |
| Grocery      | 2025-02  | 50             | 60.00          |

---

## 📈 Visualization

A bar chart was generated using Matplotlib to compare revenue per category across months.

- <a href="https://github.com/yashh1910/TASK7/blob/main/screenshot/SALES_CHART.jpeg"> SALES_CHART </a>

---

## 💡 Key Insights

- **Electronics** had significantly higher revenue compared to **Grocery**.
- Highest revenue observed in **January 2025** due to laptop sales.
- Consistent performance of grocery items across both months.

---

## ✅ Deliverables

- Python script for data analysis.
- Bar chart image: `SALES_CHART.jpeg`
- This README file.
