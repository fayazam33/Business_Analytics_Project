
# Business Analytics Dashboard

Welcome to the **Business Analytics Dashboard**, a powerful and interactive Streamlit app designed to help businesses analyze their sales, purchases, inventory, and profit data — all in one place!
---
Site Link - https://fayazam33-business-analytics-project.streamlit.app/
For dry run -->

📥 Step 1: Download CSV Files
Download the following sample CSV files:
products.csv
purchases.csv
sales.csv

🚀 Step 2: Launch the App
Click the hosted app link below to launch the dashboard:
🔗 Open the Dashboard

📂 Step 3: Upload CSV Files
Once the dashboard is open:
Click “Browse files” for each section to upload:
products.csv
purchases.csv
sales.csv

📅 Step 4: Choose Date Range
Use the date picker to select the date range you want to analyze.

🌍 Step 5: Filter by Location
Select one or more locations such as: Dhaka, Chittagong, Rajshahi, Khulna... and others

📊 Step 6: View Results
Once files are uploaded and filters applied, the dashboard will automatically display:
✅ KPIs (Revenue, Profit, ROI, etc.)
📉 Stock & Purchase vs. Sales Analysis
📦 Understocked Products
💡 Automated Product Recommendations
📍 Location-wise Performance

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

Programming Language:
Python 3.8+

Libraries and Packages:
Streamlit — For building interactive web dashboards
Pandas — Data manipulation and analysis
Plotly Express — Interactive data visualization
NumPy — Numerical computing and array operations
Base64 — Encoding CSV files for download links


