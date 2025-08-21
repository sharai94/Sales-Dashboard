# 📊 Sales Dashboard (Power BI)

## 📂 Project Structure
- 2020Sales.xlsx – source data:
  - Sales sheet – sales transactions (OrderQty, UnitPrice, LineTotal, ProductName, ProductLine, dates, and more).
  - Returns sheet – order statuses (Delivered, Lost).
- Sales Dashboard.pbix – Power BI file with visualizations.

---

## 🔄 Workflow

### 1. Data Preparation
- Imported Excel sheets Sales and Returns into Power BI.
- Joined tables using SalesOrderID.
- Created measures to calculate:
  - LineTotal (order amount),
  - number of delivered, lost, returned, and back-ordered transactions.

### 2. Data Modeling
- Aggregated data by month.
- Added breakdowns by ProductLine (M, R, S, T) and Order Status (Delivered, Lost, Returned, Back Order).

### 3. Visualizations in Power BI
- 📈 LineTotal by Month and ProductLine – monthly sales trends by product lines.
- 📉 LineTotal by Month and Order Status – order trends by status (Lost, Returned).
- ⏳ LineTotal by Month and Back Order – volume of back-ordered sales.
- 📊 KPI Cards:
  - Total Delivered: 484.14K
  - Total Lost Orders: 26.29K
  - Total Returned: 27.20K
  - Total Back Ordered: 12.89K
- 🗂 Filters:
  - by Month (time slicer),
  - by ProductName (top products with % of sales).

---

## 🎯 Result
This dashboard allows you to:
- track monthly sales trends by product lines,
- monitor lost, returned, and back-ordered sales,
- analyze performance of specific products,
- quickly evaluate key sales KPIs.
