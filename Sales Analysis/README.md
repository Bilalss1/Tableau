# 📊 Just-Store Sales Dashboard

Welcome to the **Just-Store Dashboard** – a comprehensive Tableau-powered data visualization and analytics interface designed for executive-level insights into customer activity, order flow, profit generation, and category-wise sales performance.

---

## 📂 Dashboard Overview

The dashboard is divided into two main views:

### 🔹 Executive View (Visual Summary)
- **Customers**: 247
- **Orders**: 296
- **Total Profit**: `$23K`
- **Total Sales**: `$181K`
- **Total Quantity Sold**: 3,053 units

#### Key Visual Elements:
- **Sales by Region (Bar Chart)**:
  - West: **$107,483** (Dominant)
  - East: **$41,705**
  - South: **$17,309**
  - Central: **$14,007**

- **Sales Distribution by Category (Pie Chart)**:
  - Technology: `$72,708`
  - Furniture: `$59,219`
  - Office Supplies: `$48,577`

- **Sales & Profit by Category (Grouped Bar Chart)**:
  - Technology: `$72,708` in sales with **$13,997** in profit
  - Furniture: `$59,219` in sales with **$2,341** in profit
  - Office Supplies: `$48,577` in sales with **$6,894** in profit

- **Sales Over Time (Area Chart)**:
  - March, September, and December are **peak sales months**.
  - March: `$22,108`
  - September: `$29,485`
  - December: `$25,639`

---

### 🔹 Table View (Detailed Data Table)
A detailed customer-level breakdown including:
- Customer Name
- Order ID
- Order Count
- Profit per Customer
- Sales per Customer

#### Notable Insights:
- **Top Performers by Profit**:
  - Anthony Johnson: **$480 profit** on **7 orders** totaling `$1,366`
  - Andy Reiter: **$240 profit** on **4 orders** totaling `$693`

- **Negative Profit Customers**:
  - Anthony Jacobs: `-$735` loss despite `$1,422` in sales
  - Anna Häberlin: `-$52` profit on `$793` in sales
  - Berenike Kampe: `-$180` on `$315` in sales

---

## 📌 KPIs Summary

| Metric        | Value   |
|---------------|---------|
| Customers     | 247     |
| Orders        | 296     |
| Total Profit  | $23K    |
| Total Sales   | $181K   |
| Total Quantity| 3,053   |

---

## 📈 Performance Observations

- **Technology** is the leading sales & profit category.
- **West region** dominates in regional sales (nearly 60% of total).
- **Customer Profitability** varies widely; some high-volume customers result in losses.
- **Sales Seasonality**: High spikes in March, September, and December suggest seasonal buying behavior.

---

## 🧠 Inferred Business Insights

- Profit margins on Furniture are **significantly lower** than Technology.
- Several high-spend customers are **unprofitable**, which could indicate:
  - High discounting
  - Expensive fulfillment/logistics
- **Sales optimization** could target the East and South regions for growth potential.

---

## 🛠 Suggestions or Improvements

1. **Introduce Profit Margin KPI** for more meaningful profitability analysis.
2. **Customer Segmentation** dashboard (e.g., High Profit vs High Loss) for targeted strategy.
3. **Include Return Rate/Discount Rate Metrics** to explain negative profits.
4. **Regional Trend Analysis Over Time** to track shifts in demand.
5. **Interactive Filters** (e.g., by Category, Year, Region) to enhance exploratory analysis.

---

## 🧭 Dashboard Contents (From .twbx)

- **Dashboards**:
  - Executive View
  - Table View

- **Worksheets**:
  - Customer KPI
  - Order KPI
  - Profit KPI
  - Sales KPI
  - Quantity KPI
  - Sales Over Time
  - Sales & Profit by Category
  - Sales Distribution by Category

- **Datasource**:
  - federated.1wcct3s0cvifcj1bc038x126xtdy

---

## 📹 Video Context Summary

The walkthrough video reinforces:
- Interactive controls (Region/Year filters)
- Highlighting Technology as a consistent top-performer
- Focus on September spike with further drill-down potential

---

## 🗂️ Frame Captures from Walkthrough Video

Frames extracted at regular intervals to support validation of interactive use:
- `frame_0.jpg`: Initial KPI overview
- `frame_60.jpg`: Category pie chart hover
- `frame_120.jpg`: Sales trend highlight
- `frame_180.jpg`: Table filter use
- `frame_240.jpg`: Profit sorting in table

> These can be reviewed in the `/frames/` folder for reference.

---

## ✅ How to Contribute

Feel free to:
- Fork this repo and improve the dashboard with suggested features
- Add new KPIs or visuals
- Build a predictive model using this dataset
- Enhance user interactivity with Tableau parameters

---

## 📎 File Contents

- `Sales Dashboard.twbx` - Tableau Packaged Workbook
- `Dashboard.png` - Executive View Snapshot
- `Table View.png` - Detailed Data Table Snapshot
- `Video.mp4` - Dashboard Walkthrough
- `/frames/` - Extracted video frames

---
