# Business Analytics Dashboard

Welcome to the **Business Analytics Dashboard**, a powerful and interactive Streamlit app designed to help businesses analyze their sales, purchases, inventory, and profit data — all in one place!
---
## 🚀 Project Overview
This project is a **data-driven dashboard** built using Python, Streamlit, and Plotly for visualization. It provides:

- Insights into **top-performing products** by profit.
- Visualization of **profit distribution by category**.
- Real-time tracking of **stock status** (understocked, overstocked, properly stocked).
- Highlighted stock status with color-coded HTML tables.
- Business recommendations based on inventory status and sales trends.
- Downloadable CSV reports for detailed analysis.
---
## ⚙️ Features

- Upload CSV files: `products.csv`, `sales.csv`, and `purchases.csv`.
- Filter data by date range, store location, and product category.
- Interactive charts with **Plotly** for clear visualization.
- Highlighted stock status with color-coded HTML tables.
- Business recommendations based on inventory status.
- Download buttons with styled hover effects for exporting reports.
- Responsive and clean UI with Streamlit’s layout options.
---

## 📁 Project Structure
business_dashboard/
│
├── init.py -----> Package initializer
├── dashboard_app.py ---> Streamlit dashboard frontend
├── business_analytics.py ---> Core analytics functions
├── README.md ---> Project overview and instructions
├── products.csv ---> #Product dataset
├── sales.csv ---> # Sales transactions dataset
└── purchases.csv ---># Purchase transactions dataset

🔧 How It Works
The app processes uploaded CSV files and converts dates for filtering.Filters on sidebar let you select:
Date range
Store locations (e.g., Dhaka, Chittagong)
Product categories (Groceries, Electronics, etc.)
The backend calculates KPIs like total revenue, profit, units sold, and stock status.

Visualizations show:
Top 10 products by profit (with salmon-colored bars)
Profit distribution by category (eye-catching pie chart)
Tables with color-coded stock status and suggested reorder quantities.
Download buttons allow exporting filtered reports with stylish hover effects.
Business recommendations highlight restocking and clearance actions.

