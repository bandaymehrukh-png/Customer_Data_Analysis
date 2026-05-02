# Customer Data Analysis

End-to-end retail analytics project analyzing 10,400 customer transactions using Python, MySQL and Power BI.

## 📌 Project Overview
This project simulates a real-world retail analytics workflow from data cleaning to SQL-based business intelligence and an interactive dashboard. Built to demonstrate full-stack data analysis skills for a portfolio.

## 🗂️ Repository Structure
```
├── Customer_data.ipynb                  # Python - Data cleaning & EDA
├── cleaned_customer_shopping_data.csv   # Cleaned dataset (10,400 records)
├── customer_data.sql                    # 15+ SQL queries for business analysis
├── customer_data.pbix                   # Power BI interactive dashboard
├── Customer_Data_Analysis_Report.docx   # Full written analysis report
├── Customer_Data_Analysis_PPT.pptx      # Presentation slide deck
└── README.md
```

## 🛠️ Tools & Technologies
| Tool     | Purpose                       |
|----------|-------------------------------|
| Python   | Data cleaning & EDA           |
| MySQL    | Business intelligence queries |
| Power BI | Interactive dashboard         |

## 📊 Dataset
- **Records:** 10,400 transactions
- **Source:** Synthetically generated to simulate realistic retail purchasing patterns
- **Note:** No real customer data was used. Dataset is for portfolio and educational purposes only.

## 🐍 Python: Data Cleaning & EDA
**File:** `Customer_data.ipynb`
- Imputed missing `Product Type` values using an item-to-category mapping dictionary
- Filled missing `Review Rating` with group mean per product type
- Exported cleaned dataset as `cleaned_customer_shopping_data.csv`

## 🗄️ SQL Analysis
**File:** `customer_data.sql`
- Revenue aggregation by product type, gender, season and age group
- Customer segmentation using `CASE` statements
- Discount effectiveness analysis using subqueries
- Window functions (`ROW_NUMBER() OVER`) for ranking top products per category

## 📈 Power BI Dashboard
**File:** `customer_data.pbix`
- Revenue and sales analysis page
- Customer behavior and segmentation page
- Fully interactive with slicers for gender, season and product category
