QuickBite_Food_Delivery_Analysis_Power_BI

📘 Project Overview

QuickBite Express — a Bengaluru-based food-tech startup — faced a major business disruption in June 2025. A viral food-safety scandal involving partner restaurants and a week-long delivery outage caused:

🔻 Massive order drop
💔 Customer trust breakdown
😞 Negative reviews
🏃‍♂️ Restaurant churn
⏳ Delivery delays

🎯 Project Goal

The goal is to deliver an interactive Power BI dashboard that helps QuickBite:

📊 Compare performance across Pre-Crisis, Crisis, Recovery phases
🧠 Identify customer behaviour changes
📉 Track decline in orders and ratings
👑 Find high-value customers impacted the most

📂 Dataset Description

The project uses multiple datasets such as:

🧾 Orders Table – order_id, customer_id, restaurant_id, order date, order status, order value
🚚 Delivery Table – delivery time, SLA status, delays
🧍 Customers Table – demographics, activity
🍽️ Restaurant Table – ratings, performance, loyalty flag
⭐ Reviews Table – customer ratings and feedback

🔍 Approach

2️⃣ Data Preparation

🧹 Cleaned data in Power Query
📅 Created Date Table
📌 Added Crisis Phase column using date ranges
🔗 Ensured relationships (star model)

3️⃣ Data Modeling

📦 Fact Tables: Orders, Delivery, Reviews
🧱 Dimension Tables: Customers, Restaurants, Date

4️⃣ DAX Measures

🔢 Total Orders
📊 Pre-Crisis Orders
⚠️ Crisis Orders
📉 Decline %
💸 Revenue Loss %
❌ Cancellation Rate
💬 Sentiment Score
🚫 Cancelled Orders

5️⃣ Dashboard Development

🎨 Designed clear, clutter-free visuals
🎛️ Added slicers (Month, City, Crisis Phase)
🧩 Added icons, KPIs, cards, tooltips

🛠️ Tools & Technologies

🟡 Power BI – Data modelling, DAX, dashboard creation
🔵 Power Query – ETL: Extract – Transform – Load
🧮 DAX & KPI calculations

🧩 Data Model

✔️ Star Schema
✔️ One-to-many relationships
✔️ Calendar as the primary date dimension
✔️ Segmentation using calculated columns

<img width="1430" height="689" alt="image" src="https://github.com/user-attachments/assets/7cf4438d-d9b1-41ce-ac56-2df5e2958682" />

-------------------------------------------------------------------------


📌 Key Insights

Some major findings:

📉 Orders dropped sharply from 113.8K+ per month → 35K per month
⚠️ Faced a 68.9% decline and a 70% revenue loss, resulting in a cancellation rate of 7.45%.
🔁 Repeat customers dropped significantly
⏳ SLA compliance went down
🏃‍♂️💨 Restaurateurs lost trust → partner churn

----------------------------------------------------------------------

<img width="1233" height="695" alt="image" src="https://github.com/user-attachments/assets/e5c4669f-bff2-4376-99ab-2b0cb896a624" />

<img width="1220" height="683" alt="image" src="https://github.com/user-attachments/assets/c37bda00-b116-44ff-b523-ee43a82f456d" />

<img width="1216" height="680" alt="image" src="https://github.com/user-attachments/assets/679738ff-5f52-4745-a46a-dd967b69ec61" />



