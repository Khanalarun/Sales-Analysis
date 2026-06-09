# Sales-Analysis
Data visualization of stationary sales
Stopped thinking
# 📊 Super Store Sales Analysis Dashboard

## 📌 Project Overview

The **Super Store Sales Analysis Dashboard** is an end-to-end Business Intelligence project developed using **Microsoft Power BI** and **Excel**. The objective of this project is to transform raw retail sales data into meaningful business insights through interactive visualizations, KPI tracking, trend analysis, and regional performance monitoring.

The dashboard enables stakeholders to monitor sales performance, profitability, customer segments, shipping methods, payment modes, and geographic sales distribution across different states and regions.

---

## 🚀 Project Objectives

- Analyze overall sales performance and profitability.
- Track sales trends over time.
- Identify top-performing product categories and sub-categories.
- Compare sales across customer segments.
- Evaluate shipping mode effectiveness.
- Analyze payment method preferences.
- Visualize geographical sales distribution.
- Support data-driven business decision-making.

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|--------|----------|
| Microsoft Power BI | Data Modeling & Dashboard Development |
| Microsoft Excel | Data Source & Data Preparation |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures & KPI Calculations |
| Bing Maps | Geographic Visualization |
| GitHub | Project Documentation & Version Control |

---

## 📂 Dataset Information

### Dataset Name
**SuperStore Sales Dataset**

### Source File
`SuperStore Sales DataSet.xlsx`

### Dataset Size
- Total Records: **5,901**
- Time Period: **January 2019 – December 2020**
- Features: **23 Columns**

### Key Fields

| Column |
|----------|
| Order ID |
| Order Date |
| Ship Date |
| Ship Mode |
| Customer ID |
| Customer Name |
| Segment |
| Country |
| City |
| State |
| Region |
| Product ID |
| Category |
| Sub-Category |
| Product Name |
| Sales |
| Quantity |
| Profit |
| Returns |
| Payment Mode |

---

# 📈 Dashboard Features

## 1. Executive KPI Cards

The dashboard provides a high-level overview of business performance through KPI cards:

- Total Sales
- Total Quantity Sold
- Total Profit
- Total Orders

These KPIs allow management to quickly assess overall business performance.

---

## 2. Regional Analysis

### Region Filter

Users can dynamically filter the dashboard by:

- Central
- East
- South
- West

This helps compare regional performance and identify growth opportunities.

---

## 3. Sales by Customer Segment

### Visualization:
Donut Chart

### Purpose:
Analyzes sales contribution from different customer segments.

Segments include:

- Consumer
- Corporate
- Home Office

### Business Value:
Identifies the most profitable customer groups and supports targeted marketing strategies.

---

## 4. Monthly Profit Analysis

### Visualization:
Line Chart

### Purpose:
Tracks monthly profit trends throughout the year.

### Insights:
- Identifies seasonal fluctuations.
- Detects high-profit and low-profit months.
- Supports forecasting and budgeting decisions.

---

## 5. Geographic Sales Distribution

### Visualization:
Map Chart

### Purpose:
Displays sales performance across different states in the United States.

### Business Value:
- Identify high-performing states.
- Detect underperforming regions.
- Support regional sales strategy development.

---

## 6. Payment Mode Analysis

### Visualization:
Donut Chart

### Payment Methods:
- Cash on Delivery (COD)
- Online
- Cards

### Business Value:
Provides insights into customer payment preferences and supports payment optimization strategies.

---

## 7. Monthly Sales Trend

### Visualization:
Line Chart

### Purpose:
Shows monthly sales performance over the selected period.

### Business Value:
- Detect seasonality patterns.
- Evaluate promotional campaign effectiveness.
- Forecast future sales performance.

---

## 8. Sales by Ship Mode

### Visualization:
Horizontal Bar Chart

### Shipping Modes:
- Standard Class
- Second Class
- First Class
- Same Day

### Business Value:
Analyzes customer delivery preferences and logistics efficiency.

---

## 9. Category Performance Analysis

### Visualization:
Bar Chart

### Categories:
- Office Supplies
- Technology
- Furniture

### Business Value:
Identifies the highest revenue-generating product categories.

---

## 10. Sub-Category Analysis

### Visualization:
Bar Chart

### Example Sub-Categories:
- Binders
- Appliances
- Phones
- Chairs

### Business Value:
Determines top-selling product groups and inventory priorities.

---

# 🔄 Data Preparation Process

### Step 1: Data Import
Imported the Excel dataset into Power BI.

### Step 2: Data Cleaning
Performed data quality checks:

- Removed null values
- Corrected data types
- Validated date fields
- Standardized category values

### Step 3: Data Transformation
Using Power Query:

- Created Date hierarchy
- Formatted sales and profit metrics
- Prepared location fields for map visualization

### Step 4: Data Modeling
Established relationships between dimensions and fact data.

### Step 5: DAX Calculations

Example measures:

```DAX
Total Sales =
SUM(Sales[Sales])

Total Profit =
SUM(Sales[Profit])

Total Quantity =
SUM(Sales[Quantity])

Total Orders =
DISTINCTCOUNT(Sales[Order ID])
```

---

# 📊 Key Business Insights

### Sales Performance
- Sales are concentrated within a few high-performing states.
- Significant monthly fluctuations indicate seasonal purchasing behavior.

### Customer Segments
- Consumer segment contributes the largest portion of sales.
- Corporate customers generate substantial revenue opportunities.

### Product Categories
- Office Supplies and Technology categories generate strong revenue.
- Certain sub-categories consistently outperform others.

### Logistics
- Standard Class shipping dominates customer preference.
- Same Day shipping usage remains minimal.

### Payment Trends
- COD and Online payments account for a significant share of transactions.
- Understanding payment behavior can improve customer experience.

---

# 📷 Dashboard Preview

![Sales Dashboard](Sales%20Dashboard%20screenshot.jpg)

---

# 📁 Project Structure

```text
SuperStore-Sales-Analysis/
│
├── Data/
│   └── SuperStore Sales DataSet.xlsx
│
├── Dashboard/
│   └── SuperStore Sales Dashboard.pbix
│
├── Images/
│   └── Sales Dashboard screenshot.jpg
│
└── README.md
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- KPI Development
- Dashboard Design
- Data Visualization
- Business Analysis
- Trend Analysis
- Geographic Analytics
- Storytelling with Data

---

# 💼 Portfolio Value

This project demonstrates practical Business Intelligence skills required for roles such as:

- Data Analyst
- Business Intelligence Analyst
- Reporting Analyst
- Power BI Developer
- Healthcare Data Analyst
- Operations Analyst

---

## 👨‍💻 Author

**Arun Khanal**

Aspiring Data Analyst | Power BI Developer | 

### Skills
- Power BI
- SQL
- Python
- Excel
- Data Visualization
- Healthcare Reporting
- Dashboard Development

---

⭐ If you found this project useful, feel free to star the repository and connect with me on LinkedIn.
