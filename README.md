# Power BI Data Modeling & Analytics Project
## Project Title
**Sales Analytics Dashboard using Star Schema Data Model**

## Project Objective
The objective of this project is to design a **well-structured Star Schema data model** and build an **interactive Power BI dashboard** that provides meaningful business insights into sales performance, customer behavior, product trends, and regional analysis.

This project demonstrates practical skills in:
- Data modeling
- Data cleaning & transformation
- DAX calculations
- Business intelligence reporting
- Dashboard storytelling

## Data Architecture

The project follows a **Star Schema** design for optimal performance and scalability.

### Fact Table
- **Sales_Fact**
  - Order ID
  - Order Date
  - Sales Amount
  - Quantity
  - Profit
  - Foreign keys linked to dimensions

### Dimension Tables
- **Customer_Dim**
  - Customer ID
  - Customer Name
  - Segment
  - Region

- **Product_Dim**
  - Product ID
  - Product Name
  - Category
  - Sub-Category

- **Date_Dim**
  - Date
  - Year
  - Quarter
  - Month
  - Day

- **Region_Dim**
  - Region
  - Country
  - State
  - City

## Data Relationships
- One-to-Many relationships from each **Dimension Table → Sales_Fact**
- Single-direction filtering
- Clean, normalized model to avoid ambiguity and circular dependencies

## Tools & Technologies Used
- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- **Google Sheets (Data Source)**

## Key Measures & KPIs (DAX)
- Total Sales
- Total Profit
- Profit Margin %
- Total Quantity Sold
- Average Order Value
- Sales Growth (YoY / MoM)
- Top N Products & Customers

## Dashboard Features
- Interactive slicers (Date, Region, Category)
- KPI cards for quick insights
- Bar & column charts for comparison
- Line charts for trends
- Donut charts for distribution analysis
- Clean dark/modern visual theme
