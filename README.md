# 🚚 Sales & Logistics Analytics Dashboard

---

## 📌 Project Overview
An end-to-end Business Intelligence project designed to monitor corporate sales performance, regional fulfillment, and logisitical timelines. 

The report draws data directly from a **SQL Server** relational database, transformed into a **Star Schema Data Warehouse** model to support multi-dimensional analysis, key KPIs, and detailed drill-through capability.

---

## 🏗️ Data Architecture & Star Schema Model
The data model connects a central Fact table (`Fact_OrderDetail`) to 6 Dimension tables and a dedicated DAX measure table:

- **Fact Table:** `Fact_OrderDetail
- **Dimension Tables:**
  - `Dim_Date`
  - `Dim_Product`
  - `Dim_Territory`
  - `Dim_Status`
  - `Dim_ShipMethod`
  - `SalesPerson`
- **Measure Table**

---

## 📈 Executive Summary (Key KPIs)
- **Total Orders (#Order):** 31K
- **Total Quantity Sold (#Qty):** 121K
- **SubTotal Revenue:** $110M
- **Total Freight Expenses:** $10M
- **Total Gross Revenue (TotalDue):** $123M

---

## 🔍 Visual Features & Drill-Through Capabilities

### 1. **Main Page (`Sales & Logistics`)**
- **Timeline Overview**
- **Logistics & Operations**
- **Sales Rep Performance**
- **Category Volume & Territory Breakdown**

### 2. **Drill-Through Page (`Details`)**
- Dedicated timeline drill-through page allowing users to right-click from the main trend line and analyze individual date behaviors separately:
  - **`order by Due Date`**
  - **`order by Order Date`**
  - **`order by Ship Date`**

---

## 🛠️ Tech Stack
- **Database Engine:** SQL Server
- **Data Architecture:** Data Warehouse (Star Schema Modeling)
- **BI Tool:** Power BI (DAX, Interactive Drill-Through Page Navigation)

---
