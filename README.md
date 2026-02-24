# 📦 Delivering Right, Delivering On Time | Power BI Project

**Understanding Gaps in Supply Chain Performance**

---

## 📌 Project Overview

In today’s fast-paced and competitive supply chain environment, **delivery reliability is a key driver of customer satisfaction and operational excellence**. Businesses must ensure that orders are delivered **On-Time and In-Full (OTIF)** to maintain trust, reduce churn, and optimize logistics efficiency.

This project analyzes **supply chain delivery performance using interactive Power BI dashboards**, focusing on identifying operational bottlenecks, underperforming customers, demand patterns, and OTIF gaps.

The objective is to transform raw operational data into **actionable insights** that help improve delivery reliability, customer retention, and strategic decision-making.

---

## 🎯 Project Objectives

* Measure total orders placed and delivered over time
* Calculate and monitor **On-Time Delivery (OTD)**, **In-Full Delivery (IFD)**, and **OTIF %**
* Identify patterns in late and incomplete deliveries
* Detect underperforming customers, cities, and product categories
* Compare actual performance against customer OTIF targets
* Analyze weekday vs weekend delivery performance
* Provide strategic recommendations to improve OTIF rate

---

## 🛠 Tools & Technologies

* **Power BI** – Data Modeling & Dashboard Development
* **DAX (Data Analysis Expressions)** – KPI & Target Calculations
* **Power Query** – Data Cleaning & Transformation
* **Star Schema Data Model** – Fact & Dimension tables

---

## 📈 Key Metrics Tracked

* **Total Orders**
* **Successful OTIF %**
* **Failed OTIF Orders**
* **On-Time %**
* **In-Full %**
* **Target Gap Analysis (OTIF, OTD, IFD)**
* **City-wise & Category-wise Order Volume**
* **Delay Distribution by Days**

---

## 🔍 Key Insights from the Dashboard

### 🔹 Overall Delivery Performance

* **Total Orders:** 57K
* **Successful OTIF:** 65.05%
* **Failed OTIF Orders:** 30K
* **Maximum Delay Observed:** 3 Days

**Insight:**
A significant portion of orders fail OTIF compliance, indicating operational inefficiencies that require targeted intervention.

---

### 🔹 Customer Performance Analysis

* **Best Served Customer:** Propel Mart
* **Poorly Fulfilled Customer:** Lotus Mart
* **Total Customers:** 35

**Insight:**
Certain customers consistently experience delivery gaps, increasing churn risk. Targeted operational improvements can enhance retention.

---

### 🔹 Product & Category Analysis

* **Top Ordered Product:** AM Milk 250
* **Least Ordered Product:** AM Ghee 100
* **Highest Demand Category:** Dairy (10.6M orders)

**Insight:**
High-demand products and categories require stronger inventory planning and logistics prioritization.

---

### 🔹 City-wise Order Distribution

* **Top Cities:** Vadodara & Ahmedabad (~4.6M orders each)

**Insight:**
Logistics capacity should be optimized in high-volume cities to prevent delivery delays.

---

### 🔹 Day-wise Order & Delivery Trends

* **Most Orders Placed On:** Tuesday
* **Most Expected Delivery Day:** Thursday
* **Most Deliveries Completed On:** Weekends

**Insight:**
Workforce and logistics planning must focus on mid-week demand peaks and weekend fulfillment loads.

---

## 📊 Dashboard Features

### 🏠 Overview Page

* KPI Cards (Total Orders, OTIF %, Failed Orders)
* Gauge Chart (Target vs Actual)
* Category & City-wise Analysis
* Seasonal Order Trends

### 👥 Customer Insights

* Customer-level OTIF breakdown
* Delay distribution
* Top & bottom customer comparison

### 🛒 Product Insights

* Product demand analysis
* Category performance
* Product-level delay table

### 📦 Order Insights

* Orders placed vs delivered (day-wise)
* % of delayed orders
* On-Time, In-Full & OTIF comparison

---

## 🧮 Sample DAX Calculation

```DAX
OTIF_Percentage =
DIVIDE(
    CALCULATE(
        COUNTROWS(fact_order_lines),
        fact_order_lines[On Time In Full] = 1
    ),
    COUNTROWS(fact_order_lines)
) * 100
```

Other calculated metrics include:

* OnTime_Percentage
* InFull_Percentage
* Failed_OTIF_Orders
* Target Gap Analysis

---

## 🔎 Root Cause Analysis

Identified potential causes for OTIF failures:

* Weekend delivery overload
* Operational bottlenecks
* Mode of transport inefficiencies
* Unrealistic customer expectations
* Inventory misalignment

---

## 🛠 Strategic Recommendations

* Increase weekday manpower allocation
* Improve logistics visibility using tracking tools
* Focus on high-risk customers (e.g., Lotus Mart)
* Strengthen supplier collaboration
* Conduct regular OTIF KPI reviews
* Align delivery commitments with operational capacity

---

## 📌 Business Impact

✔ Enables proactive OTIF monitoring
✔ Reduces operational inefficiencies
✔ Improves customer satisfaction
✔ Supports data-driven supply chain decisions
✔ Enhances strategic planning & demand forecasting

---

## 📷 Dashboard Preview

<img width="2247" height="1151" alt="image" src="https://github.com/user-attachments/assets/647ce451-d1c8-4cc3-a855-dec98e12019d" />

Customer Insights:

<img width="1272" height="722" alt="image" src="https://github.com/user-attachments/assets/b62c8b68-0968-48e4-a14c-2c08bc98f1ef" />

Product Insights:

<img width="1229" height="740" alt="image" src="https://github.com/user-attachments/assets/3d2ff9e5-245e-4dfc-8f00-ac1cb4b35adf" />

Order Insights:

<img width="1292" height="756" alt="image" src="https://github.com/user-attachments/assets/8789fd8e-a3d4-4075-94c6-e16800989e8c" />




---

## 🚀 Conclusion

This project demonstrates how **Power BI transforms supply chain delivery data into strategic insights**. By analyzing OTIF performance, customer behavior, and operational gaps, organizations can improve delivery reliability, increase customer retention, and achieve supply chain excellence.

Continuous monitoring, data-driven decision-making, and targeted operational improvements can significantly raise OTIF performance beyond industry benchmarks.

---

## 👩‍💼 Author

**Arya Chavan**

