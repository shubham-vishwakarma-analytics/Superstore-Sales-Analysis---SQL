# 📊 Superstore SQL Analysis

## 📌 Project Overview
This project analyzes the **Superstore Dataset** using **SQL Server**.
The aim is to derive meaningful business insights with **advanced SQL queries** such as:
- Total Sales & Profit trends
- Top & second-highest performing products
- Customer purchase behavior
- Shipping performance

---

## 🗂 Repository Structure
```
├── datasets/   # Superstore source data
├── queries/    # All SQL queries used for analysis
├── images/     # Query output screenshots
└── README.md
```

---

## 🗃 Dataset
Dataset Source: [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

Local copy: [`datasets/Superstore.csv`](datasets/Superstore.csv)

---

## 📂 Files
- [Analysis.sql](queries/Analysis.sql) → All queries used for analysis

---

## 📷 Query Outputs
**1️⃣ Total Sales & Profit by Category** ![Total Sales and Profit by Category](images/Q1.png)
**2️⃣ Top 5 Customers by Total Profit** ![Top 5 Customers by Total Profit](images/Q2.png)
**3️⃣ Monthly Sales Trend** ![Monthly Sales Trend](images/Q3.png)
**4️⃣ Profit by Region** ![Profit by Region](images/Q4.png)
**5️⃣ Top 5 Products by Quantity Sold** ![Top 5 Products by Quantity Sold](images/Q5.png)
**6️⃣ Top 5 Customers by Highest Total Sales** ![Top 5 Customers by Total Sales](images/Q6.png)
**7️⃣ Monthly Sales Trend (with Profit)** ![Monthly Sales Trend with Profit](images/Q7.png)
**8️⃣ Year-over-Year (YoY) Growth in Sales** ![Year-over-Year Growth in Sales](images/Q8.png)
**9️⃣ Top 5 Profitable Products** ![Top 5 Profitable Products](images/Q9.png)
**🔟 Loss-Making Products** ![Loss-Making Products](images/Q10.png)
**1️⃣1️⃣ Regional Performance with Ranking** ![Regional Performance with Ranking](images/Q11.png)
**1️⃣2️⃣ Customer Segmentation** ![Customer Segmentation](images/Q12.png)
**1️⃣3️⃣ Shipping Speed Impact on Profit** ![Shipping Speed Impact on Profit](images/Q13.png)
**1️⃣4️⃣ Top 3 Customers in Each Region** ![Top 3 Customers in Each Region](images/Q14.png)
**1️⃣5️⃣ Second Highest Sales per Region** ![Second Highest Sales per Region](images/Q15.png)
**1️⃣6️⃣ Second Highest Product by Total Sales** ![Second Highest Product by Total Sales](images/Q16.png)

---

## 🔑 Key SQL Concepts Used
- **CTEs & Subqueries** – reusable query blocks
- **Window Functions** – RANK, DENSE_RANK, LAG
- **Aggregations** – SUM, COUNT, AVG, GROUP BY
- **Joins** – combining multiple tables
- **Filtering & Sorting** – advanced WHERE + ORDER BY
