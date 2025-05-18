# 🛒 Hypermart Sales Dashboard – Power BI Project

## 📌 Project Overview

This Power BI project simulates a real-world scenario where the owner of a hypermart chain wants to **track and analyze online sales across India**. The goal was to build an **interactive and insightful sales dashboard** to empower data-driven business decisions.

>  **Disclaimer:** The data used in this project is **not from an actual hypermart**. It was sourced from the internet for **educational and learning purposes only**.

---

## 🎯 Project Objectives

- Build a **visually interactive dashboard** for online sales analysis.
- Apply the complete Power BI workflow: **data import, modeling, visualization,analysis**.
- Derive insights that support **data-driven business decisions**.

---

## 📁 Datasets Used

### 1. `Details.csv`
This file contains **order-level transaction details** and metrics like:
- `Order ID`: Unique identifier for each order
- `Amount`: Revenue generated from the order
- `Profit`: Profit earned from that order
- `Quantity`: Number of units sold
- `Category` & `Sub-Category`: Type of product sold (e.g., Clothing → Saree)
- `PaymentMode`: Payment method used (e.g., UPI, COD, Debit Card)

### 2. `Orders.csv`
This file provides **customer and geographic details** for each order:
- `Order ID`: Key to join with `Details.csv`
- `Order Date`: Date of purchase
- `Customer Name`: Name of the buyer
- `State` & `City`: Location where the order was delivered


---

## ⚙️ Power BI Workflow

### 🔹 1. Data Import
- Imported both datasets into **Power BI Desktop**.

### 🔹 2. Data preprocessing & Modeling
- Verified field types (e.g., date, text, numeric) and column roles.
- Created a **relationship** between the two tables using `Order ID`.

### 🔹 3. DAX Calculations
Created multiple measures and calculated columns, such as:
- `Total Sales Amount`
- `Total Profit`
- `Total Quantity`
- `Average Order Value`
- Month-wise and Quarter-wise summaries

### 🔹 4. Dashboard Development
Designed a **clean and interactive dashboard** featuring:
- KPI Cards, Bar Charts, Pie Charts
- **Two slicers** for filtering:
  - **Quarter-wise performance**
  - **State-wise performance**

---

## 🧠 How This Dashboard Helps the Hypermart Owner

The dashboard enables the owner to:

- 📍 Identify **Top 3 States by Sales** (e.g., Maharashtra, Madhya Pradesh, Uttar Pradesh)
- 📦 Discover which **product category** (e.g., Clothing) is **most popular**
- 📅 Analyze **monthly sales trends** and identify **peak months** (e.g., December)
- 🎯 Focus marketing efforts on **low-performing months or sub-categories**
- 💳 Understand **preferred payment methods** (e.g., UPI leads with 43.74%)
- 🧑‍💼 Track **high-value customers** by sales contribution

These insights allow the hypermart to make **informed decisions** regarding inventory, promotions, and regional targeting.

---

## 🔄 Project Flow

### ✅ Upstream (Input)
- Raw files: `Details.csv`, `Orders.csv`
- Initial inspection and cleansing

### 📊 Downstream (Output)
- Fully functional Power BI Dashboard with:
  - Sales & Profit analysis
  - Customer & State-wise views
  - Time-based performance tracking

---

## 🛠️ Tools Used

- Microsoft Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Microsoft Excel (for initial data exploration)

---

## 🖼️ Dashboard Preview

> 📎 Check out `Hypermarket Dashboard.pdf` included in this report to see a snapshot of the final dashboard.

---

Thank you!
