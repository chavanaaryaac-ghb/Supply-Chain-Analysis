📌 Project Overview

Timely and complete deliveries are critical for supply chain excellence. This project analyzes On-Time In-Full (OTIF) performance using Power BI to identify operational gaps, customer impact, and improvement opportunities.

The dashboard provides insights into delivery reliability, customer performance, product demand, and operational bottlenecks using a data-driven approach.

🎯 Problem Statement

In today’s fast-moving and competitive market:

Customer expectations are high.

Delays and incomplete deliveries impact credibility.

Lack of real-time visibility causes operational inefficiencies.

Common challenges include:

Fragmented logistics

Weekend delivery bottlenecks

Poor OTIF monitoring

Underperforming customer segments

This project aims to monitor, analyze, and improve delivery performance using interactive Power BI dashboards.

🎯 Objectives

Measure total orders placed and delivered over time.

Calculate On-Time Delivery (OTD), In-Full Delivery (IFD), and OTIF rates.

Identify late delivery patterns.

Detect underperforming customers, cities, and product categories.

Compare actual performance vs agreed customer targets.

Analyze weekend vs weekday logistics impact.

Provide data-backed strategic recommendations.

🏗️ Methodology
1️⃣ Data Connection

Connected structured datasets into Power BI.

2️⃣ Data Cleaning

Removed inconsistencies

Handled missing values

Standardized formats

3️⃣ Data Modeling

Star schema model using:

fact_order_lines

dim_targets_orders

Customer and product dimensions

4️⃣ Data Processing & DAX Calculations

Key Metrics:

OTIF_Percentage =
DIVIDE(
    CALCULATE(COUNTROWS(fact_order_lines),
    fact_order_lines[On Time In Full] = 1),
    COUNTROWS(fact_order_lines)
) * 100

Other KPIs include:

OnTime_Percentage

InFull_Percentage

Failed OTIF %

Late Orders

InFull Target Gap

OnTime Target Gap

OTIF Target Gap

📊 Dashboard Features
🏠 Overview Page

Total Orders: 57K

Failed OTIF Orders: 30K

Successful OTIF: 65.05%

Most Orders Placed: Tuesday

Most Expected Delivery Day: Thursday

Most Deliveries Done: Weekends

📍 City Insights

Vadodara & Ahmedabad lead in order volume.

Dairy category has highest demand (10.6M orders).

Peak demand observed in May.

👥 Customer Insights

Total Customers: 35

Best Served Customer: Propel Mart

Poorly Fulfilled Customer: Lotus Mart

Delay distribution by customer

Customer-level OTIF breakdown

🛒 Product Insights

Top Product: AM Milk 250

Least Ordered Product: AM Ghee 100

Category-wise order trends

Product-level delay analysis

📦 Order Insights

Orders Placed vs Delivered (Weekday Analysis)

% of Delayed Orders

Customer-level performance table

OTIF breakdown by order type

🔍 Key Findings

30K orders failed OTIF compliance.

Most delayed deliveries occur around peak weekday expectations.

Some customers show consistent OTIF underperformance.

High On-Time deliveries sometimes still fail In-Full criteria.

Operational gaps exist in manpower allocation and logistics scheduling.

🛠 Root Cause & Recommendations
🔹 Operational Improvements

Increase weekday manpower (especially before Thursday peaks).

Improve logistics planning for high-demand cities.

Enhance transport allocation for peak categories.

🔹 Strategic Actions

Improve service quality for underperforming customers (e.g., Lotus Mart).

Set clearer delivery expectations.

Use advanced tracking for better visibility.

Conduct regular OTIF performance reviews.

📈 Business Impact

This dashboard enables:

Proactive OTIF monitoring

Reduced delivery failures

Improved customer retention

Data-backed logistics optimization

Alignment with contractual delivery targets

Dashboard:
<img width="2247" height="1151" alt="image" src="https://github.com/user-attachments/assets/647ce451-d1c8-4cc3-a855-dec98e12019d" />

Customer Insights:
<img width="1272" height="722" alt="image" src="https://github.com/user-attachments/assets/b62c8b68-0968-48e4-a14c-2c08bc98f1ef" />

Product Insights:
<img width="1229" height="740" alt="image" src="https://github.com/user-attachments/assets/3d2ff9e5-245e-4dfc-8f00-ac1cb4b35adf" />

Order Insights:
<img width="1292" height="756" alt="image" src="https://github.com/user-attachments/assets/8789fd8e-a3d4-4075-94c6-e16800989e8c" />




📌 Conclusion

Power BI enabled deep insights into:

Customer performance

Product demand

Delivery timing gaps

OTIF success and failure rates

With continuous monitoring and strategic intervention, OTIF performance can improve from 65% to industry-leading benchmarks.
