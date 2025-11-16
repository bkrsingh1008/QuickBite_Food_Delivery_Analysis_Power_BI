# QuickBite_Food_Delivery_Analysis_Power_BI
----------------------------------------------
📘 Project Overview

QuickBite Express — a Bengaluru-based food-tech startup — faced a major business disruption in June 2025. A viral food-safety scandal involving partner restaurants and a week-long delivery outage caused:

Massive order drop
Customer trust breakdown

Negative reviews

Restaurant churn

Delivery delays

Competitor advantage

This project analyzes Pre-Crisis vs Crisis vs Recovery performance using Power BI to help QuickBite leadership understand:

✔ What went wrong
✔ Which segments were impacted most
✔ Which customers/restaurants to target in recovery
✔ How operations & ratings changed
✔ Where immediate improvements are needed

🎯 Project Goal

The goal is to deliver an interactive Power BI dashboard that helps QuickBite:

Compare performance across Pre-Crisis, Crisis, Recovery phases

Identify customer behaviour changes

Track decline in orders and ratings

Find high-value customers impacted the most

Measure delivery efficiency (SLA, delays, average delivery time)

Identify partner restaurants at risk

Recommend strategies to rebuild trust and improve retention

📂 Dataset Description

The project uses multiple datasets such as:

Orders Table – order_id, customer_id, restaurant_id, order date, order status, order value

Delivery Table – delivery time, SLA status, delays

Customers Table – demographics, activity

Restaurant Table – ratings, performance, loyalty flag

Reviews Table – customer ratings and feedback

Date Table – custom calendar with crisis phases

🔍 Approach
1️⃣ Identifying Crisis Phases

Created 3 segments:

Pre-Crisis: Jan–May 2025

Crisis: Jun–Sep 2025

Recovery: Oct–Dec 2025

2️⃣ Data Preparation

Cleaned data in Power Query

Created Date Table

Added Crisis Phase column using date ranges

Ensured relationships (star model)

3️⃣ Data Modeling

Fact Tables: Orders, Delivery, Reviews

Dimension Tables: Customers, Restaurants, Date

Relationship: Date ↔ Orders as primary

4️⃣ DAX Measures

Total Orders

Pre-Crisis Orders

Crisis Orders

Decline %

Avg Delivery Time

SLA Breach %

Repeat Customer Rate

Restaurant Retention Score

5️⃣ Dashboard Development

Designed clear, clutter-free visuals

Added slicers (Month, City, Crisis Phase)

Added icons, KPIs, cards, tooltips

🛠️ Tools & Technologies
Tool	Purpose
Power BI	Data modelling, DAX, dashboard creation
Excel	Initial cleaning and exploration
SQL (optional)	Data filtering and transformation
Power Query	ETL: Extract – Transform – Load
DAX	Time intelligence & KPI calculations
🧩 Data Model

✔ Star Schema
✔ One-to-many relationships
✔ Calendar as the primary date dimension
✔ Segmentation using calculated columns

📌 Key Insights

Some major findings:

Orders dropped sharply from 23K+ per month → 9K per month

Average delivery time increased during the crisis

Ratings fell due to delays & food-safety scare

High-value customers churned at highest rate

Repeat customers dropped significantly

SLA compliance went down

Restaurateurs lost trust → partner churn

Crisis impact started recovering slowly from October
