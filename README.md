# 🧾 Retail Sales Analysis – Power BI Project

## 📊 Project Overview
This project provides a **comprehensive retail performance analysis** across multiple regions, categories, and time periods using **Power BI**.  
It highlights key sales metrics, profitability trends, and customer purchasing patterns to uncover actionable insights that drive **data-driven business decisions**.

The analysis focuses on **sales performance between 2022–2024** across four major regions — East, West, North, and South — with detailed segmentation by **product category** and **seasonality**.

---

## 🎯 Objective
To analyze the company’s **retail sales performance** and identify:
- Year-over-year growth trends in **sales, profit, and order volume**
- **Regional contribution** to overall business performance
- **Product category growth rates** and **seasonal demand variations**
- The **impact of discount strategies** on total revenue and profitability

---

## 🧩 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data modeling, visualization, DAX calculations |
| **Excel / CSV Data Source** | Raw transactional sales data |
| **Power Query Editor** | Data transformation and cleaning |
| **DAX (Data Analysis Expressions)** | Calculated columns, KPIs, and measures |
| **GitHub** | Project documentation and portfolio showcase |

---

## 🧮 Data Model & Schema

### Dataset Fields
| Field | Description |
|--------|-------------|
| Store ID | Unique identifier for store location |
| Product ID | Unique identifier for each product |
| Category | Product category (Furniture, Electronics, Clothing, etc.) |
| Date | Transaction date |
| Region | Business region (East, West, North, South) |
| Seasonality | Season derived from transaction date |
| Units Ordered / Sold | Quantity ordered and sold |
| Total Sales | Gross revenue per transaction |
| Profit | Net profit per transaction |
| Profit % | Profitability margin |

### Data Modeling
- Built **relationships** between Date, Product, and Region tables.  
- Created **hierarchies** for Year → Quarter → Month to support time-series analysis.  
- Defined **calculated columns** for:
  - `Profit Margin = DIVIDE([Profit], [Total Sales])`
  - `YoY Sales Growth = ([Sales CY] - [Sales PY]) / [Sales PY]`

---

## 📈 Dashboard Insights

### 1. Executive Summary
- **Total Sales (CY)**: ₹274M (vs ₹276M previous year)
- **Total Orders**: 4M (↑ 101% YoY)
- **Total Profit**: ₹88M (↑ 99% YoY)
- Overall growth across major KPIs, indicating strong **recovery and expansion** in FY 2024.

---

### 2. Regional Analysis
| Region | Total Sales | Orders | Profit | Contribution |
|---------|--------------|--------|---------|---------------|
| East | ₹138.7M | 2.02M | ₹44.4M | 25% |
| North | ₹137.3M | 1.99M | ₹44.0M | 25% |
| South | ₹138.5M | 2.02M | ₹44.5M | 25% |
| West | ₹135.8M | 2.01M | ₹43.5M | 25% |

📍 **Insight:** Performance is **balanced across regions**, showing consistent operational efficiency. South and East regions slightly outperform others in profitability.

---

### 3. Category-Wise Analysis
| Category | Growth % | Contribution |
|-----------|-----------|--------------|
| Furniture | 101% | 21% |
| Groceries | 96% | 20% |
| Clothing | 101% | 20% |
| Toys | 98% | 20% |
| Electronics | 101% | 19% |

📊 **Insight:**  
- **Furniture and Electronics** lead in growth rate, indicating successful product strategies.  
- **Groceries** show marginally lower growth, possibly due to market saturation or pricing competition.

---

### 4. Seasonal Trends
Sales distribution across seasons:
- **Autumn** and **Spring** recorded the **highest order volumes**, driven by festival and holiday demand.
- **Winter** showed steady performance, while **Summer** indicated a moderate dip in sales.

🕒 **Business Recommendation:**  
Plan promotional campaigns around **Spring and Autumn** to leverage peak purchase periods.

---

### 5. Discount Impact Analysis
| Metric | Observation |
|---------|--------------|
| Total Orders | Increased with moderate discount offers |
| Profit | Improved marginally, suggesting discount strategies were cost-effective |
| Total Sales | Increased proportionally with discounts |

💡 **Insight:**  
Discounts led to **boosted order volumes** without significantly eroding profit margins — an indicator of **optimized promotional planning**.

---

## 📚 Advanced Power BI Features Used
- **Dynamic Filters and Slicers** for Region, Category, and Seasonality  
- **DAX Measures** for calculating YoY growth, profit %, and discount impact  
- **Drillthrough Pages** for detailed category-level exploration  
- **Bookmarks and Reset Buttons** for intuitive navigation  
- **KPI Cards and Line Charts** for tracking performance over multiple years  
- **Interactive Tooltips** for contextual insights  

---

## 🧠 Key Insights & Business Recommendations
1. Maintain **balanced inventory distribution** across regions since performance is uniform.  
2. Focus marketing spend on **top-performing categories** like Furniture and Electronics.  
3. Utilize **discount campaigns during low-performing months** (e.g., Summer).  
4. Monitor **Groceries segment** closely for declining growth trends.  
5. Continue leveraging **seasonal trends** for strategic promotions.

---

## 🧾 Conclusion
This Power BI project demonstrates advanced data storytelling through:
- Clear visualization of KPIs  
- Actionable business insights  
- Use of interactive dashboards  
- Integration of advanced DAX calculations  

It reflects **data analytics proficiency in transforming complex datasets into strategic intelligence** for business decision-making — suitable for **retail domain analytics** roles.

---

