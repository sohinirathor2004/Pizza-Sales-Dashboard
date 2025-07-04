# 🍕 Pizza Sales Dashboard (Power BI + MS SQL Server)

<img width="605" alt="part1pizza dashboard" src="https://github.com/user-attachments/assets/0c55caa8-e48c-4333-bf8b-125c6767f6c4" />


<img width="612" alt="part2pizzadashboard" src="https://github.com/user-attachments/assets/54ab5eb4-7369-45dc-8c80-2fe913960d51" />


## 📌 Overview

This project presents an **interactive Pizza Sales Dashboard** built using **Power BI** for data visualization and **Microsoft SQL Server** for backend data processing. It analyzes pizza sales data from **January to December 2015**, enabling data-driven insights into revenue, quantity, and order patterns.

---

## 📊 Key Metrics

- **Total Revenue**: ₹817.86K
- **Average Order Value**: ₹38.31
- **Total Pizzas Sold**: 49,574
- **Total Orders**: 21,350
- **Avg. Pizzas per Order**: 2.32

---

## 🏆 Best Sellers

- **Highest Revenue Pizza**: Thai Chicken
- **Most Sold (Quantity)**: Classic Deluxe
- **Most Frequently Ordered**: Classic Deluxe

---

## 📉 Worst Sellers

- **Lowest Revenue Pizza**: Brie Carre
- **Least Sold (Quantity)**: Brie Carre
- **Least Ordered**: Brie Carre

---

## 📌 Dashboard Features

- 📅 Interactive date range filter (Jan–Dec 2015)
- 🍕 Pizza Category selector
- 📈 Top & Bottom 5 pizzas by:
  - Revenue
  - Quantity Sold
  - Total Orders
- 💡 KPI Cards for summary insights
- 🎯 Clear and color-coded visual storytelling

---

## 🛠 Tech Stack

- **Database**: Microsoft SQL Server
- **Visualization Tool**: Power BI Desktop
- **Data Source**: Pizza Sales Transactional Dataset (CSV → SQL)
- **Query Language**: T-SQL (for joins, aggregations, transformations)

---

## ▶️ How to Use

To run and explore this dashboard on your local system:

1. **Clone or Download** this repository.

2. **Set up the SQL Server database**:
   - Create a new database in MS SQL Server.
   - Import the pizza sales dataset (CSV file or `.bak` file if provided).
   - Use the provided SQL script (optional) to clean, join, and transform the data.

3. **Open the Power BI file** (`.pbix`) in Power BI Desktop.

4. **Connect to your SQL Server**:
   - Go to `Home` → `Transform Data` → `Data source settings`.
   - Change the connection string to match your local SQL Server instance.
   - Apply and refresh queries.

5. **Explore the Dashboard**:
   - Use filters (date range, pizza category) to interact with visuals.
   - Hover over KPIs and charts for detailed tooltips.
   - Export visuals or reports as needed

## 💡 Future Improvements

- Add dynamic drill-through pages for category and product details
- Integrate predictive analytics for sales forecasting
- Deploy to Power BI Service with automatic refresh
- Add Row-Level Security (RLS) for role-based views

---

