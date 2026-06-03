📊 Sales Performance Dashboard

Overview
Interactive sales analytics dashboard analyzing 12 months 
of FY 2024 data across 120 orders, 5 product categories, 
and 4 regions.

Dashboard Preview
![Dashboard](screenshots/dashboard_final.png)

Key Insights
- 💰 Total Revenue: ₹33.7L across 120 orders
- 📈 Technology drives 82% of total revenue
- 📉 Q3 revenue dip of 23% linked to high discounts
- 🏆 Laptops and Phones are top sub-categories
- 🌍 South region contributes 74% of all orders

Tools Used
| Tool | Purpose |
| Power BI Desktop | Dashboard, charts, KPI cards |
| DAX | Measures — Revenue, Profit, Margin, MoM Growth |
| SQLite + DB Browser | SQL queries for data extraction |
| Python Pandas | Data cleaning and EDA |
| Microsoft Excel | Initial data review |

DAX Measures
- Total Revenue = SUM(Sales)
- Total Profit = SUM(Profit)
- Profit Margin % = DIVIDE(Profit, Revenue) * 100
- Total Orders = COUNTROWS(table)
- Avg Order Value = DIVIDE(Revenue, Orders)

SQL Queries
4 queries written in SQLite covering:
- Monthly revenue and profit trend
- Revenue by category and region
- Discount impact on profit margin
- Top 10 products by revenue

Files
- `SalesDashboard.pbix` — Power BI file (open to interact)
- `sales_data_clean.csv` — Raw dataset (120 rows, 16 cols)
- `SalesDashboard_preview.pdf` — PDF preview
- `sql_queries/` — All 4 SQL query files
- `screenshots/` — Dashboard and query result screenshots

Author
Mukesh.S | BCA Graduate 2025 | Data Analyst
📍 Chennai, Tamil Nadu
🔗 www.linkedin.com/in/mukesh-sm-ms
