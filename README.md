# 🛒 Amazon Global Sales Dashboard

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-2C5F9E?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

**An interactive Business Intelligence Dashboard analyzing Amazon's Global Sales Performance from 2012 to 2015.**

</div>

---

## 📸 Dashboard Preview

![Amazon Global Sales Dashboard](https://raw.githubusercontent.com/princesi22/Amazon-sales-dashboard/main/amazon%20sale%20dashboard%20with%20map.png)

---

## 📌 Project Overview

The **Amazon Global Sales Dashboard** delivers a comprehensive, interactive analysis of sales performance, profit distribution, customer behavior, and product profitability across global markets and business segments.

Built in **Power BI**, this dashboard empowers stakeholders to make **data-driven decisions** by surfacing critical insights across four years of Amazon's global operations (2012–2015).

---

## 🎯 Business Objectives

| # | Objective |
|---|-----------|
| 1 | Analyze year-over-year sales growth from 2012 to 2015 |
| 2 | Identify top revenue-generating markets worldwide |
| 3 | Understand profit distribution at the city level |
| 4 | Detect best and worst performing products by profitability |
| 5 | Evaluate high-value customer contributions |
| 6 | Track and reduce product return rates |

---

## 📊 Key Performance Indicators (2013 Snapshot)

<div align="center">

| 💰 Total Sales | 📦 Product Quantity | 📈 Total Orders | 🔁 Returns |
|:--------------:|:-------------------:|:---------------:|:----------:|
| **₹2.68M** | **3.087K** | **38K** | **369** |

</div>

> 💡 *KPI values update dynamically based on the Year Filter (2012–2015).*

---

## 📈 Dashboard Insights

### 🏷️ Sales by Segment

| Segment | Sales | Share |
|---------|-------|-------|
| 🔵 Consumer | ₹1.46M | 54.67% |
| 🟠 Corporate | ₹0.77M | 28.93% |
| 🔴 Home Office | ₹0.44M | 16.40% |

The **Consumer segment dominates**, generating over half of all revenue — a clear signal for where to concentrate marketing and product investment.

---

### 🌎 Sales by Market

| Market | Sales | Share |
|--------|-------|-------|
| 🌏 Asia Pacific | ₹863.98K | 32.27% |
| 🌍 USCA | ₹717.61K | 26.80% |
| 🌍 Europe | ₹486.63K | 18.18% |
| 🌎 LATAM | ₹464.73K | 17.36% |
| 🌍 Africa | (remaining) | ~5.39% |

**Asia Pacific** leads all markets, making it the primary revenue engine for global growth strategy.

---

### 🏆 Top 5 Profitable Products

```
1. Fellowes PB ...    ████████████████████  ~5K profit
2. Zebra ZM4 ...      ██████████████        
3. Samsung S ...      ████████████          
4. Nokia Smar...      ██████████            
5. Samsung S ...      ████████              
```

---

### 📉 Bottom 5 Products (Loss-Making)

```
1. Cubify Cube...     ████  ~2K loss
2. Bevis Confer...    ███               
3. Chromcraft...      ██                
4. Chromcraft...      ██                
5. Hon Round ...      █                 
```

> ⚠️ These products are actively dragging down profitability and should be reviewed for discontinuation or repricing.

---

### 👥 Top Customers by Profit

Highest-profit customers include: **Mike Gock**, **Keith Dawk**, **Ellis Ballard**, **Fred Hopkins**, and others — forming a valuable **top-tier customer cohort** for retention and upsell programs.

---

## 🗺️ Geographic Coverage

The interactive map visualizes **bubble-sized sales volumes** across regions including:

- 🌏 Asia & Southeast Asia
- 🌍 Europe & Africa
- 🌎 North America, Latin America & South America

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 📊 **Power BI Desktop** | Dashboard design, KPI cards, charts & interactive visualizations |
| 📂 **Microsoft Excel** | Raw dataset storage, data organization & preprocessing |
| 🔄 **Power Query Editor** | Data cleaning, transformation, column formatting & shaping |
| 📈 **DAX** | Custom KPI measures, calculated columns & aggregations |

---

## 📂 Dataset Structure

The dataset covers the following dimensions:

- **Orders** — Order ID, date, ship mode
- **Customers** — Customer name, segment, region
- **Products** — Category, sub-category, product name
- **Geography** — Market, region, country, city
- **Financials** — Sales, profit, quantity, discount
- **Returns** — Return flag and return counts

---

## 🚀 Getting Started

```bash
# Step 1: Clone the repository
git clone https://github.com/princesi22/Amazon-sales-dashboard.git

# Step 2: Open in Power BI Desktop
# File → Open → amazon sale dashboard with map.pbix

# Step 3: Interact with the dashboard
# Use the Year Filter (2012–2015) to explore trends
```

> **Requirements:** Power BI Desktop (free) — [Download here](https://powerbi.microsoft.com/desktop)

---

## 💡 Key Learnings

- ✅ Data Cleaning & Transformation using **Power Query Editor**
- ✅ Connecting & loading data from **Excel** into Power BI
- ✅ Writing custom **DAX measures** for KPIs and calculated columns
- ✅ Building dynamic **KPI Cards** in Power BI
- ✅ Creating **Interactive Slicers** for year-based filtering (2012–2015)
- ✅ Designing a professional, dark-themed **Dashboard UI** in Power BI
- ✅ Visualizing geographic sales performance with **Map Visuals**
- ✅ Extracting actionable **Business Insights** from raw sales data

---

## 📌 Conclusion & Recommendations

> From 2012–2015, the **Consumer segment** and **Asia Pacific market** were the primary revenue drivers.

**Strategic Recommendations:**

| Priority | Action |
|----------|--------|
| 🎯 High | Double down on Asia Pacific market expansion |
| 📦 High | Increase inventory & marketing for top-selling products |
| 🚫 Medium | Discontinue or reprice bottom 5 loss-making products |
| 🔁 Medium | Investigate return root causes to reduce the 369 return rate |
| 👥 Low | Launch VIP retention program for top-profit customers |

---

## 👤 Author

**Prince**
📊 Aspiring Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-princesi22-181717?style=flat-square&logo=github)](https://github.com/princesi22)

*Skills: Data Analytics · Power BI · DAX · Power Query · Excel*

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

</div>
