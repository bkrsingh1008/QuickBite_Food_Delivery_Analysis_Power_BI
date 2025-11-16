QuickBite_Food_Delivery_Analysis_Power_BI

📘 Project Overview
-------------------------------------

QuickBite Express — a Bengaluru-based food-tech startup faced a major business disruption in June 2025. A viral food-safety scandal involving partner restaurants and a week-long delivery outage caused:

🔻 Massive order drop
💔 Customer trust breakdown
😞 Negative reviews
🏃‍♂️ Restaurant churn
⏳ Delivery delays

🎯 Project Goal
-----------------------------------------

The goal is to deliver an interactive Power BI dashboard that helps QuickBite:

📊 Compare performance across Pre-Crisis, Crisis, Recovery phases
🧠 Identify customer behaviour changes
📉 Track decline in orders and ratings
👑 Find high-value customers impacted the most

📂 Dataset Description
---------------------------------------

The project uses multiple datasets such as:

🧾 Orders Table – order_id, customer_id, restaurant_id, order date, order status, order value
🚚 Delivery Table – delivery time, SLA status, delays
🧍 Customers Table – demographics, activity
🍽️ Restaurant Table – ratings, performance, loyalty flag
⭐ Reviews Table – customer ratings and feedback

🔍 Approach
------------------------------------------

1️⃣ Data Preparation

🧹 Cleaned data in Power Query
📅 Created Date Table
📌 Added Crisis Phase column using date ranges
🔗 Ensured relationships (star model)

2️⃣ Data Modeling

📦 Fact Tables: Orders, Delivery, Reviews
🧱 Dimension Tables: Customers, Restaurants, Date

3️⃣ DAX Measures

🔢 Total Orders
📊 Pre-Crisis Orders
⚠️ Crisis Orders
📉 Decline %
💸 Revenue Loss %
❌ Cancellation Rate
💬 Sentiment Score
🚫 Cancelled Orders

4️⃣ Dashboard Development

🎨 Designed clear, clutter-free visuals
🎛️ Added slicers
🧩 Added icons, KPIs, cards, tooltips

🛠️ Tools & Technologies
----------------------------------------------

🟡 Power BI – Data modelling, DAX, dashboard creation
🔵 Power Query – ETL: Extract – Transform – Load
🧮 DAX & KPI calculations

🧩 Data Model
---------------------------------------------

✔️ Star Schema
✔️ One-to-many relationships
✔️ Calendar table
✔️ Calculated columns

<img width="1430" height="689" alt="image" src="https://github.com/user-attachments/assets/7cf4438d-d9b1-41ce-ac56-2df5e2958682" />

-------------------------------------------------------------------------


📌 Key Insights
--------------------------------------------

Some major findings:

📉 Orders dropped sharply from 113.8K+ per month → 35K per month
⚠️ Faced a 68.9% decline and a 70% revenue loss, resulting in a cancellation rate of 7.45%.
🔁 Repeat customers dropped significantly
⏳ SLA compliance went down
🏃‍♂️💨 Restaurateurs lost trust → partner churn

----------------------------------------------------------------------

<img width="1266" height="706" alt="image" src="https://github.com/user-attachments/assets/d4c03ea0-09a8-450f-9de0-2364856e9eb2" />

<img width="1216" height="682" alt="image" src="https://github.com/user-attachments/assets/ad6e2f4c-feda-4c0b-954f-0a7893be8240" />

<img width="1241" height="682" alt="image" src="https://github.com/user-attachments/assets/a10690ae-8d4a-44d7-a91d-2bf0d316c656" />




