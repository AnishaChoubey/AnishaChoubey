## Customer 360° Dashboard
1. HUSK Customer 360° Dashboard
   
   An interactive and visually rich data visualization tool designed to analyze customer energy consumption, recharge patterns, and service performance—empowering operational teams, customer service, and management with actionable insights.

2. Short Description / Purpose
   
   The HUSK Customer 360° Dashboard is a comprehensive Power BI report built to monitor customer profiles, energy usage trends, and payment behavior. It enables stakeholders to proactively address service issues, optimize tariff plans, and enhance customer satisfaction by providing a unified view of key operational and financial metrics.

5. Tech Stack
   
   The dashboard was built using the following tools and technologies:

   📊 Power BI Desktop – Main platform for interactive reporting and visualization.

   📂 Power Query – Data cleaning, transformation, and shaping.

   🧠 DAX (Data Analysis Expressions) – Calculated measures for energy usage, uptime, and performance KPIs.

   📝 Data Modeling – Established relationships between customer master, transaction, and consumption datasets.

   📁 File Format – .pbix for development and .png for dashboard previews.

   ☁ Azure SQL Database & Blob Storage – Cloud storage and structured query processing for real-time data.

4. Data Source
   Source:

   CRM system for customer profiles (name, joining date, plan details, contact info)
   Payment and recharge transaction logs
   Hourly smart meter readings for energy usage
   Complaint management records

5. Data Structure:

   Customer Master Table: Profile details, meter info, tariff plan
   Transaction Table: Recharge amount, credited amount, top-up history
   Consumption Table: Hourly readings for consumed energy (kWh) and true power (W)
   Service Records: Complaints, uptime hours

6. Features / Highlights
   Business Problem

   Customer energy consumption data, recharge history, and service issues were siloed across multiple systems, making it difficult for operations, sales, and customer support teams to track performance, resolve complaints, and identify usage patterns efficiently.

   Goal of the Dashboard

   To provide an interactive single-pane view of all key customer metrics—consumption trends, recharge behavior, and service uptime—enabling proactive engagement, optimized resource planning, and data-driven decision-making.

   Walkthrough of Key Visuals

   Customer Profile Panel (Top Left): 
   Displays key customer details: Name, contact info, joining date, plan type, meter ID, tariff details, and recharge status.

   Recharge History Table (Center Left):
   Month-wise breakdown of revenue, paid amount, credited amount, number of top-ups, and energy units consumed.

   Avg Consumed Energy (kWh) vs Hour (Top Right):
   Line chart showing hourly average energy usage for different months to track customer consumption patterns over time.

   Max Consumed Energy (kWh) vs Hour (Middle Right):
   Identifies the peak consumption hours for each month, useful for load management and capacity planning.

   Avg True Power & Max True Power (W) vs Hour (Bottom)
   Visualizes load stability and usage spikes, aiding in identifying unusual consumption patterns.

   Complaint & Uptime Summary (Top Right):
   Displays total complaints and average uptime hours, allowing quick assessment of service reliability.

   Time Period Filters (Top Bar):  
   Enables users to switch between Month-to-Date (MTD), Last 1M, Last 2M, Last 3M, and Last 6M views to analyze trends.

7. Business Impact & Insights
   
   Operational Efficiency: Centralized monitoring reduces time spent retrieving data from multiple systems.

   Customer Retention: Early identification of abnormal consumption trends enables proactive support and engagement.

   Revenue Optimization: Helps evaluate plan suitability and identify potential tariff adjustments.

   Service Reliability: Improves tracking of uptime and complaint resolution times, leading to higher customer satisfaction.

8. Screenshot
   
   Dashboard_Preview:  [https://github.com/AnishaChoubey/AnishaChoubey/blob/main/Customer_dashboard.png](url)
<!--
**AnishaChoubey/AnishaChoubey** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
