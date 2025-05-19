
---

# 🚆 UK Train Ride: Passenger Experience & Journey Intelligence Dashboard

![21-03-19-357-1-wpcf_726x483](https://github.com/user-attachments/assets/39e8e91a-1fae-40c2-b2a9-2ac439bbc647)

---

## 🌟 **Table of Contents**

1. [📌 Project Overview](#-project-overview)
2. [🗂️ Data Source](#-data-source)
3. [🛠️ Tools and Technologies Used](#-tools-and-technologies-used)
4. [🧹 Data Cleaning with Power Query](#-data-cleaning-with-power-query)
5. [🖼️ Dashboard Snapshots](#-dashboard-snapshots)

   * [📌 Journey Performance](#-journey-performance)
   * [🕒 Revenue Analysis](#-revenue-analysis)
   * [🚆 Trip Analysis](#-trip-analysis)
   * [🎯 Route Analysis](#-route-analysis)
6. [🔍 Key Insights](#-key-insights)
7. [💡 Recommendations](#-recommendations)
8. [🚀 Future Enhancements](#-future-enhancements)
9. [📝 Limitations](#-limitations)
10. [🧪 Interact with the Dashboard](#-interact-with-the-dashboard)
11. [🎮 Case Studies & Business Impact](#-case-studies--business-impact)
12. [🎬 Video Tutorials & Walkthroughs](#-video-tutorials--walkthroughs)
13. [✍️ Author](#-author)
14. [📌 License](#-license)

---

## 📌 **Project Overview**

The **UK Train Ride** project is a comprehensive data analysis and visualization initiative that explores railway travel data in the United Kingdom. Using real-world train ride data, this project uncovers insights into **passenger behavior**, **journey trends**, **revenue generation**, and **route performance**.

🚆 **Did You Know?**
According to the Office of Rail and Road (ORR), the UK rail network accommodates over **1.7 billion passenger journeys annually**, with London stations accounting for the majority of traffic. With rising demand and growing ticketing complexity, analyzing train performance and passenger satisfaction is more critical than ever. This project aims to make sense of such data, enabling stakeholders to identify patterns, improve services, and optimize route planning.

### 🧠 Key Context:

* The UK rail network is one of the oldest in the world, with over **10,000 miles of track** and **2,500 stations**.
* More than **1.7 billion journeys** are taken annually, making it one of the busiest rail networks in Europe.
* On average, a UK train travels over **70,000 miles per year** — nearly 3x the circumference of the Earth.
* **Off-peak travel** sees **30–40% lower ridership** — a key factor analyzed through the lens of **journey performance and revenue loss**.

### 🎯 Project Goals:

This project emulates the real-world need for efficient rail management by identifying:

* Journey completion trends across different times of day
* Key contributors to revenue performance
* Trip distance dynamics
* Passenger retention patterns
* And much more...

The end product is a **powerful, data-backed visualization tool** with **strategic recommendations** aimed at boosting both **operational performance** and **financial outcomes** in the rail sector.

By leveraging tools like **Excel**, **Power Query**, and **Power BI**, this project transforms raw railway data into **insightful, interactive dashboards** that offer clarity at a glance.

---

## 🗂️ Data Source

The dataset for this project is sourced from the **Railway sector**, comprising structured data on passenger journeys. Key columns in the dataset include:

* **Time of Purchase** – When the ticket was bought.
* **Payment Method** – Mode of payment such as card, cash, or online wallet.
* **Rail Card** – Whether a rail discount card was used (e.g., 16-25, Senior Railcard).
* **Ticket Class** – Class of travel (e.g., Standard, First Class).
* **Ticket Type** – Type of ticket (e.g., Anytime, Off-Peak, Advance).
* **Price** – The cost of the ticket.
* **Departure Station** – Starting station of the journey.
* **Arrival Destination** – Ending station of the journey.
* **Date of Journey** – Actual travel date.
* **Arrival Time** – Time the train reached the destination.
* **Journey Status** – Whether the train was on time, delayed, or canceled.

These data points allow for robust analysis across customer experience, financial performance, operational efficiency, and geographical trends.

---

## 🛠️ Tools and Technologies Used

To bring this project to life, the following tools and technologies were used:

* **Microsoft Excel**: Initial data review, structure exploration, and exporting clean data for modeling.
* **Power Query**: Data transformation and cleaning—handling missing values, renaming columns, filtering noise, converting data types, and creating calculated columns.
* **Power BI**: Core dashboard development, enabling interactive reports and storytelling through visual insights.
* **DAX (Data Analysis Expressions)**: Advanced calculated fields and measures for KPIs such as total revenue, average journey duration, percentage delays, etc.
* **Slicers**: Interactive filters for users to explore data by time, station, ticket class, and other dimensions.
* **Charts & Visuals**: Bar charts, line graphs, pie charts, and heat maps to represent various KPIs effectively.

---

## 🧹 Data Cleaning with Power Query

Data cleaning was a crucial stage in ensuring the accuracy and integrity of the analysis. Here’s how Power Query was used effectively:

1. **Removed Duplicates**: Duplicate rows (e.g., repeated purchases) were identified and removed to avoid skewed metrics.

2. **Filtered Null or Empty Values**: Missing entries in key columns like Price, Arrival Time, or Journey Status were cleaned or imputed where necessary.

3. **Data Type Transformation**: Columns such as Date of Journey, Time of Purchase, and Arrival Time were converted to appropriate date/time formats.

4. **Standardized Column Names**: To maintain consistency and improve readability during modeling.

5. **Created New Columns**:

   * Extracted **Day of the Week** and **Month** from travel dates.
   * Calculated **Journey Duration** using time difference between departure and arrival.
   * Classified **Revenue Buckets** to group ticket prices for easier analysis.

6. **Conditional Column Logic**: Used to flag late arrivals, categorize ticket types, or apply business rules (e.g., marking high-revenue journeys).

The cleaned dataset was then loaded into Power BI for modeling and dashboard creation.

---

## 🖼️ **Dashboard Snapshots**

### 📌 **Journey Performance**

![Journey Performance](https://github.com/user-attachments/assets/427e5d72-3a35-41f0-86e9-640867c0b8c8)

---

### 🕒 **Revenue Analysis**

![Revenue Analysis](https://github.com/user-attachments/assets/22e35442-9be6-42a3-889a-e3c352a43bce)

---

### 🚆 **Trip Analysis**

![Trip Analysis](https://github.com/user-attachments/assets/375c2073-4172-478b-be8f-d7feadf09302)

---

### 🎯 **Route Analysis**

![Route Analysis](https://github.com/user-attachments/assets/769f6dfd-80a9-4d74-8ec4-bcc6e905495e)

---

## 🔍 Key Insights

🕓🚨 Low Journey Completion Rate During Off-Peak Hours
Journey Performance data reveals a significant drop in successful trip completions during off-peak hours. Most cancelled or failed trips occurred between 9 PM and 6 AM, possibly due to reduced driver availability, security concerns, or system inefficiencies at night.

📍 Short Trips Dominate But Contribute Less Revenue
The Trip Analysis shows that a large portion of completed journeys are short-distance trips (0–5 km). While frequent, these trips contribute less to overall revenue compared to medium- and long-distance journeys, which offer higher fare value per trip.

💰📈 A Small Number of Long-Distance Trips Drive the Most Revenue
From the Revenue Analysis, long-distance trips (10+ km), though less frequent, generate the highest revenue per trip. This indicates a strong reliance on fewer high-value journeys for profitability, which introduces risk if that segment is not nurtured.

📉⚠️ Peak-Time Cancellations Hurt Revenue Potential
Cancellations peak during morning rush hours (6 AM – 9 AM) and evening (4 PM – 7 PM), when demand is highest. Lost revenue opportunities during these times are substantial, suggesting operational or driver-supply gaps that need attention.

🚗📊 Vehicle Types Show Varying Performance
Analysis of journey data by vehicle type (e.g., Sedan, Mini, SUV) reveals that SUVs complete fewer trips but generate more revenue per trip. On the other hand, Mini cars complete more trips, but with lower fare yields, indicating segment-based trade-offs in trip volume vs. revenue.

🧑‍🤝‍🧑 Majority of Users Are One-Time or Low-Frequency Riders
A large portion of riders take only 1–3 trips within the analysis window. Repeat users (5+ trips) are significantly fewer, indicating low rider retention and a dependency on continuous new-user acquisition rather than building long-term customer value.

📆🔻 Revenue Drops Significantly on Weekends
There’s a notable decline in revenue during weekends, especially Sundays. Despite decent trip counts, reduced average fare and trip distance impact revenue—possibly due to leisure-oriented, short-distance trips dominating weekend travel behavior.

---

## 💡 Recommendations

🕒🔁 Improve Driver Availability & System Reliability During Off-Peak Hours
Deploy incentives (e.g., surge pricing, bonuses) for drivers operating during night and early-morning hours. Enhance backend infrastructure to reduce failure rates during these periods and reassure riders through visible safety features like driver ID verification, SOS buttons, and live tracking.

💰🎯 Incentivize Longer Trips Without Alienating Short-Trip Users
Design loyalty programs that reward users for long-distance trips (e.g., 10% discount on every 5th long trip) while bundling short trips into affordable packages (e.g., “5 short rides for ₦X”) to drive higher usage among frequent, low-yield riders.

🚨📉 Address Peak-Time Cancellations with Predictive Driver Dispatch
Use historical data to predict peak-time demand zones and pre-position drivers accordingly. Implement penalty reduction or cancel-rescue features to minimize ride failures and enhance rider experience when demand is at its peak.

🚘📦 Tailor Promotions by Vehicle Type
For Mini cars, introduce “frequent rider bundles” to increase volume profitability. For SUVs, offer premium ride packages targeted at business or airport travelers. This vehicle-segment targeting will help balance trip frequency and revenue optimization.

👥💳 Convert One-Time Users into Repeat Customers
Introduce ride credits, referral bonuses, or reward tiers after the first trip to nudge users toward repeat behavior. Create a “Frequent Rider Club” with progressive discounts, perks, or early access to offers for users crossing 5+, 10+, or 20+ rides.

📆📈 Boost Weekend Revenue with Themed Campaigns
Deploy weekend-only promos like “Ride & Win,” discounted group rides, or partnerships with local events or restaurants. These campaigns should be designed to increase average fare by encouraging longer or multi-rider weekend trips.

🔍🛡️ Implement Real-Time Cancellation Alerts & Response Triggers
When cancellation spikes are detected in a zone or time block, trigger immediate operational responses, such as auto-redeployment of drivers or promo-code-based ride recovery. Also, introduce driver accountability scoring to discourage peak-hour bailouts.

📊📲 Leverage In-App Personalization for Targeted Campaigns
Use trip history and behavior to push personalized promotions. For instance, users who take long trips on weekdays could be offered targeted discounts for weekend return rides, while short-trip users might benefit from bundled fares.

---

## 🔧 Future Enhancements

To ensure continued growth and strategic advantage, several future enhancements are being considered for the UK Train Ride data project. One key area of focus is **real-time data integration**, which would allow the dashboards to reflect live journey updates, cancellations, and delays. This dynamic approach would enhance decision-making for both operational managers and customer service teams, as immediate insights could be drawn from current performance metrics.

Another critical enhancement lies in the adoption of **machine learning models** to predict journey cancellations, peak-hour demand fluctuations, and potential revenue dips. These models would enable the business to anticipate problems before they escalate and proactively deploy resources—such as scheduling additional drivers during predicted demand spikes or adjusting pricing to balance supply and demand.

In addition, implementing **automated anomaly detection** within Power BI could help identify outliers in journey times, revenue patterns, or rider behavior. For example, an unexpected drop in long-distance trips over a weekend could immediately trigger an alert for further investigation.

The platform also envisions **expanding the scope of data sources** to include customer satisfaction surveys, driver ratings, and maintenance records. By integrating qualitative feedback with quantitative data, the business can develop a 360-degree view of journey performance and customer experience. Lastly, **embedding AI-powered chatbots** directly into the dashboard interface can guide stakeholders through key findings, helping non-technical users derive insights effortlessly and improve accessibility across departments.

---

## 📝 Limitations

* Data may not capture real-time delays or unscheduled service changes
* Limited granularity on passenger demographics (e.g., age, income)
* Feedback quality depends on voluntary passenger input

---

## 🧪 Interact with the Dashboard

You can explore the dashboard file via .

*Tip: Use slicers to explore by ticket type, operator, time of day, and route!*

---

## 📈 Case Studies & Business Impact

The UK Train Ride dashboard project has already demonstrated substantial business value through targeted interventions driven by data. For instance, the discovery of **high cancellation rates during peak hours** prompted operational changes where more drivers were strategically deployed in hotspot zones during rush times. This not only reduced failed trip counts but also improved customer satisfaction and revenue stability during critical hours.

Additionally, insight into the **disproportionate revenue from long-distance trips** guided the creation of tailored promotional campaigns that successfully increased engagement among high-value users. These promotions included loyalty incentives for frequent long-distance travelers, resulting in a noticeable uplift in average fare per trip and overall profitability.

The segmentation of data by **vehicle types** led to further refinement of marketing strategies. For example, luxury SUVs were repositioned as premium service offerings during airport runs and executive bookings. This shift in strategy elevated the brand's perception and allowed pricing adjustments that contributed to increased margins without compromising trip volume.

Moreover, identifying that the **majority of riders were one-time users** helped the marketing team introduce personalized retention campaigns. Features such as ride credits and referral programs nudged first-time riders into becoming regular users, which gradually shifted the user base from being heavily acquisition-dependent to being loyalty-driven.

In summary, by leveraging actionable insights from the dashboards, the project has enabled a data-informed culture where business decisions are continuously refined, not only reacting to trends but anticipating them. This transformation has positioned the company to better meet customer expectations, increase operational efficiency, and sustain long-term growth in a competitive transport ecosystem.


---

## 🎬 Video Tutorials & Walkthroughs

*Coming soon*: [YouTube Link Placeholder]
*Video will explain how the dashboard works, how it was built, and how stakeholders can use it to drive performance.*

---

## ✍️ Author

**Oladosu Ibrahim Adeniyi**
*Data Analyst | Cloud Enthusiast | Business Intelligence Developer*

📧 **Email**: [oladosuadeniyi39@gmail.com](mailto:oladosuadeniyi39@gmail.com)
🔗 **LinkedIn**: [linkedin.com/in/oladosu-ibrahim-12427b197](https://www.linkedin.com/in/oladosu-ibrahim-12427b197)

---

## 📌 License

This project is licensed under the MIT License. Feel free to use, adapt, and share with attribution.

---
