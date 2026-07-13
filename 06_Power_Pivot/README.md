# 📊 Excel Power Pivot Portfolio

A hands-on collection of Excel Power Pivot projects demonstrating data modeling, DAX calculations, relationships, and Time Intelligence functions. These projects simulate real-world business reporting scenarios using a star schema data model.

---

## 📂 Project Structure

```text
06_Power_Pivot/
│
├── Datasets/
│   ├── Customers.csv
│   ├── Date.csv
│   ├── Products.csv
│   ├── Sales_Fact.csv
│   ├── Stores.csv
│   └── Superstore_Data.xlsx
│
├── 01_PowerPivot_Fundamentals.xlsx
├── 02_Time_Intelligence_DAX.xlsx
└── README.md
```

---

# 📘 Project 1 — Power Pivot Fundamentals

### Overview

This workbook demonstrates how to build a complete Power Pivot data model from multiple related tables and create reusable DAX measures for business reporting.

### Skills Demonstrated

- Importing multiple tables into the Data Model
- Building Star Schema relationships
- Creating one-to-many relationships
- Writing DAX Measures
- Creating Pivot Tables from the Data Model
- Business KPI calculations
- Working with Measures instead of Calculated Fields

### Data Model

Tables included:

- Customers
- Products
- Stores
- Date
- Sales_Fact

Relationship Type:

- Star Schema

### DAX Measures

- Total Sales
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Total Profit
- Profit Margin
- Electronics Sales
- Online Hub Sales

### Example Reports

- Monthly Net Revenue
- Quarterly AOV
- Profit Margin by Month
- Profit by Gender
- Profit by Product Category

---

# 📅 Project 2 — Time Intelligence using DAX

### Overview

This project focuses on Time Intelligence calculations in Power Pivot using a dedicated Calendar table and DAX date functions.

### Skills Demonstrated

- Creating Calendar Table
- Creating Date Relationships
- Using Time Intelligence functions
- Year-over-Year analysis
- Month-over-Month analysis
- Dynamic filtering using Pivot Tables

### Time Intelligence Measures

- Total Sales
- YTD (Year-To-Date)
- QTD (Quarter-To-Date)
- MTD (Month-To-Date)
- SAMEPERIODLASTYEAR()
- PREVIOUSMONTH()

### Example Reports

- Sales by Year
- Monthly Sales
- Same Month Previous Year
- Previous Month Comparison
- YTD Analysis
- QTD Analysis
- MTD Analysis

---

## 🛠 Tools Used

- Microsoft Excel
- Power Pivot
- Data Model
- DAX (Data Analysis Expressions)
- Pivot Tables

---

## 📚 Key Concepts Practiced

- Data Modeling
- Star Schema Design
- Relationships
- DAX Measures
- Filter Context
- Row Context
- Time Intelligence
- Business KPIs
- Interactive Pivot Reporting

---
