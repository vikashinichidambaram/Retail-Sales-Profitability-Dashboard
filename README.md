<h1 align="center">📊 Retail Sales & Profitability Dashboard</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
</p>

---

## 📌 Project Overview

Developed an interactive **Retail Sales & Profitability Dashboard** using Power BI to analyze sales, profitability, products, customers, and store performance.

The project demonstrates practical skills in **Power Query, Data Modeling, DAX, and Power BI Visualizations**.

**Dataset:** Simulated retail sales data created for learning and dashboard development.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Modeling**

---

## 🖼️ Dashboard Preview

![Executive Dashboard](images/executive-dashboard.png)

---

## 📄 Dashboard Pages

| Page | Description |
|------|-------------|
| **DAX & KPI Analysis** | KPI cards, Previous Month Sales, Sales Growth %, and Product Ranking |
| **Sales Overview** | Monthly Sales Trend, Sales by Category, and Sales by Store |
| **Product Analysis** | Top 10 Products, Sales by Category, Profit by Product, and Product Performance |
| **Customer Analysis** | Top 10 Customers, Customer Segment Analysis, and Customer Performance |
| **Executive Dashboard** | Summary of key KPIs, trends, products, customers, and store performance |

### 🎛️ Slicers

- Year
- Store
- Category
- Customer Segment

---

## 🧹 Data Preparation

Used **Power Query** to:

- Clean and transform raw data
- Change and validate data types
- Remove unnecessary data
- Prepare tables for analysis

---

## 🔗 Data Model

The project follows a **Star Schema** approach.

### Fact Table

- FactSales

### Dimension Tables

- DimProduct
- DimCustomer
- DimStore
- DimDate

Relationships were created between the fact and dimension tables to support accurate analysis.

---

## 📐 DAX Measures

Created DAX measures for:

- Total Sales
- Total Cost
- Total Profit
- Total Orders
- Total Customers
- Total Quantity Sold
- Profit Margin %
- Average Order Value
- Product Ranking
- Previous Month Sales
- Sales Growth %

### Example DAX

```DAX
Total Sales =
SUMX(
    FactSales,
    FactSales[Quantity] * FactSales[UnitPrice] *
    (1 - FactSales[Discount])
)
```

---

## 🎯 Key Insights

The dashboard helps identify:

- Top-performing products
- Top customers
- Sales trends
- Store performance
- Customer segments
- Overall sales and profitability

---

## 👩‍💻 Author

**Vikashini KC**
🔗 https://github.com/vikashinichidambaram
💻 https://linkedin.com/in/vikashini-k-c-37971b267
