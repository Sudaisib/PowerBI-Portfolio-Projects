
---

# 💼 CRM Sales Opportunities: Sales Performance & Pipeline Intelligence Dashboard

![Dashboard Header](https://github.com/user-attachments/assets/84124143-0969-41bf-baf9-4d33ced84892)

---

## 🌟 Table of Contents

1. [📊 Project Overview](#-project-overview)
2. [📂 Data Source](#-data-source)
3. [🛠 Tools & Technologies](#-tools--technologies)
4. [🔍 Data Cleaning](#-data-cleaning)
5. [🖼️ Dashboard Snapshots](#-dashboard-snapshots)

   * [📈 Sales Performance – Monthly Analysis](#-sales-performance--monthly-analysis)
   * [📊 Sales Performance – Quarterly Analysis](#-sales-performance--quarterly-analysis)
   * [👤 Sales Pipeline – Monthly Performance by Rep](#-sales-pipeline--monthly-performance-by-rep)
   * [🔁 Sales Pipeline – Conversion Rate (%)](#-sales-pipeline--conversion-rate-)
   * [🧍‍♂️ Agent Performance Overview](#-agent-performance-overview)
6. [🔍 Key Insights](#-key-insights)
7. [✅ Recommendations](#-recommendations)
8. [🚀 Future Enhancements](#-future-enhancements)
9. [📝 Limitations](#-limitations)
10. [📞 Interact with the Dashboard](#-interact-with-the-dashboard)
11. [🎮 Case Studies & Business Impact](#-case-studies--business-impact)
12. [🎬 Video Tutorials & Walkthroughs](#-video-tutorials--walkthroughs)
13. [✍️ Author](#-author)
14. [📌 License](#-license)

---

## 📊 **Project Overview**

The **CRM Sales Opportunities Dashboard** is an end-to-end business intelligence solution built to empower sales leaders with visibility into opportunity trends, pipeline health, product performance, and team effectiveness. Leveraging data from core CRM modules such as Accounts, Sales Team, Products, and the Sales Pipeline, this dashboard provides a centralized, interactive platform for **tracking, forecasting, and optimizing sales opportunities**.

This project enables business users to monitor the **sales funnel**, identify bottlenecks, assess **win/loss trends**, and compare performance across teams, timeframes, and product lines. Executives can use this dashboard to guide decision-making around **resource allocation, pipeline prioritization, and strategic account management**.

The analysis breaks down opportunities by **sales stage**, **product line**, **assigned salesperson**, and **account value**, offering a clear understanding of **which leads are converting**, **where deals are stalling**, and **which teams are driving revenue growth**. Through intuitive visualizations, filters, and dynamic bookmarks, this tool transforms raw CRM data into **actionable insights** that strengthen pipeline performance and close more deals.

Ultimately, this dashboard acts as a **sales enablement system**—bridging the gap between sales activity and business outcomes to drive smarter selling, stronger forecasting, and higher revenue.

---

## 📂 **Data Source**

* **Accounts Dataset** – Company/client profiles including account names, industries, and deal sizes
* **Sales Pipeline Dataset** – Opportunity records, sales stages, expected revenue, close dates, and status
* **Sales Team Dataset** – Team member names, roles, targets, and assigned opportunities
* **Products Dataset** – Products associated with each opportunity including categories, price tiers, and volumes

---

## 🛠 **Tools & Technologies**

* **Microsoft Excel** – Data structure mapping and preprocessing
* **Microsoft Power BI** – Dashboard design, DAX modeling, and visualization
* **Power Query** – ETL processes for data cleaning and transformation
* **DAX (Data Analysis Expressions)** – KPI modeling, custom calculations, and metrics logic
* **Slicers & Bookmarks** – For interactivity, navigation, and dynamic filtering
* **Charts & Visuals** – Used to display trends, comparisons, and drilldowns

---

## 🔍 **Data Cleaning**

Data preparation was performed using **Power Query** and Excel preprocessing to ensure data integrity and consistency across multiple CRM datasets. Key steps included:

* Removal of duplicate records, blanks, and inconsistencies across joined tables
* Merging opportunity data with product and account details using unique IDs
* Conversion of text-based dates and currency fields into standardized formats
* Creation of calculated columns for **Sales Stage Duration**, **Deal Age**, and **Expected Close Category**
* Filtering of outdated or non-relevant deals (e.g., opportunities marked as “abandoned”)
* Categorization of opportunities by deal size (e.g., small, medium, enterprise)

---

## 🖼️ **Dashboard Snapshots**

### 🧾 Summary

These dashboards provide a comprehensive view of sales activities, performance metrics, and pipeline health. They are designed to reveal patterns in opportunity stages, agent performance, product conversion, and revenue contribution across different time periods—monthly and quarterly. The visualizations help decision-makers quickly identify strengths, gaps, and areas needing intervention.

---

### 📈 **Sales Performance – Monthly Analysis**

![Sales Performance (with Montly Analysis)](https://github.com/user-attachments/assets/10784bf4-29aa-44a2-a312-4f6226530a94)

*Interactive snapshot showcasing open, won, and lost opportunities by sales stage, deal value, and monthly timeline.*

### 📊 **Sales Performance – Quarterly Analysis**

![Sales Performance (with Quarter Analysis)](https://github.com/user-attachments/assets/cffd6acc-30e5-4b3b-917d-e4deca3eb5dd)

*Funnel visualization with KPIs highlighting conversion rates, deal velocity, and quarterly pipeline movement.*

### 👤 **Sales Pipeline – Monthly Performance by Rep**

![Sales Pipeline (with Monthly Performance)](https://github.com/user-attachments/assets/92d2971c-dc75-46dc-918c-6faaa2534200)

*Overview of each salesperson’s performance including win/loss ratios, average deal size, closed deals, and progress against targets.*

### 🔁 **Sales Pipeline – Conversion Rate (%)**

![Sales Pipeline (with Conversion Rate %)](https://github.com/user-attachments/assets/f0e8212c-8f0b-4c6f-bc72-cd1be25a6596)

*Insights into how different stages of the sales pipeline perform, with emphasis on stage-wise drop-offs and progression trends.*

### 🧍‍♂️ **Agent Performance Overview**

![Agent Performance](https://github.com/user-attachments/assets/65c4742c-0972-4b0d-a921-3465e433c0b6)

*Evaluation of top-performing and underperforming sales agents based on opportunity volume, conversion success, and revenue impact.*

---

## 🔍 **Key Insights**

📈 **Sales Pipeline Is Heavily Weighted Toward Early-Stage Opportunities**
A significant number of deals are concentrated in early stages like Qualification and Needs Analysis. This suggests a strong top-of-funnel activity but may indicate inefficiencies or bottlenecks in advancing deals through the pipeline.

💰 **Won Opportunities Drive the Highest Revenue Contribution**
Closed-Won deals account for the majority of revenue generated. This emphasizes the importance of nurturing mid-to-late stage opportunities to successful closure, especially in high-value segments.

📉 **Win Rate Declines Sharply After Proposal Stage**
Opportunities tend to drop off after the Proposal/Price Quote stage. This may reflect issues with pricing, perceived value, or competitive losses. A deeper win/loss analysis is required to diagnose causes.

📊 **Key Sales Contributors Show High Deal Volume but Varying Conversion Rates**
Some sales reps have high deal volume but lower win rates, while others close fewer but more valuable deals. This imbalance may point to training needs or misaligned opportunity assignments.

📆 **Quarterly Trends Show Fluctuating Performance**
Sales performance shows spikes in certain quarters (e.g., Q2 and Q4), indicating potential seasonality or reliance on end-of-quarter pushes. The inconsistency could mask underlying process or forecasting issues.

🧭 **Lost Deals Are Highest in Late Stages**
A large portion of lost revenue comes from deals that reached advanced stages before being lost. This reflects wasted sales effort and underscores the need for improved qualification and objection handling early in the cycle.

📍 **Top Territories Generate Disproportionate Revenue**
Revenue is concentrated in specific regions or customer segments. This concentration can create dependency risk and suggests opportunities for diversification and targeted market expansion.

---

## ✅ **Recommendations**

🎯 **Optimize the Sales Funnel by Addressing Late-Stage Drop-offs**
Analyze lost opportunities post-Proposal stage to identify common objections, pricing concerns, or competitor wins. Train reps on closing techniques, and arm them with ROI calculators or revised pricing strategies.

🚀 **Focus on Advancing Deals Through the Pipeline, Not Just Filling It**
With a high concentration in early-stage opportunities, introduce stricter lead qualification criteria and implement deal acceleration strategies (e.g., time-bound offers, customer success stories) to move deals forward.

📈 **Improve Forecasting Accuracy Through Win Rate Calibration**
Use historical win/loss data by stage and rep to improve pipeline forecasting. Assign weighted probabilities based on actual conversion performance, not generic assumptions.

👥 **Tailor Coaching Based on Rep Performance Patterns**
Segment sales reps by deal size, conversion rate, and cycle time. Offer personalized coaching: high-volume/low-conversion reps need deal prioritization training, while low-volume/high-value reps can be leveraged for strategic accounts.

📅 **Design Campaigns to Counter Quarter-End Dependency**
If revenue peaks in Q2 and Q4, design campaigns, incentives, or product launches to stimulate demand in Q1 and Q3. Aim to flatten the revenue curve and improve cash flow consistency.

📊 **Implement Win/Loss Feedback Mechanism**
Introduce structured feedback collection from prospects, especially for late-stage losses. This can help identify issues with pricing, competitor positioning, or misaligned proposals.

🌍 **Diversify Market Focus Beyond High-Performing Regions**
Launch pilot programs in underperforming territories with localized strategies and incentives. Reducing dependency on a few regions can unlock new revenue streams and stabilize long-term growth.

🔄 **Use AI-Powered Scoring to Prioritize High-Value Deals**
Leverage opportunity scoring models to identify deals with the highest likelihood of closing and the highest revenue impact. Focus resources on nurturing these high-priority leads.

📬 **Automate Follow-Ups and Proposal Re-engagements**
Given the high loss rate after the Proposal stage, implement automation tools (e.g., reminder emails, case studies, success stories) to re-engage prospects and maintain deal momentum.

---

## 🚀 **Future Enhancements**

* Integration of forecast modeling for expected revenue by region and team
* Advanced lead scoring to prioritize high-conversion opportunities
* Drill-through views for individual opportunity history and communications
* CRM live connection for real-time pipeline monitoring

---

## 📝 **Limitations**

* Static data snapshots – dashboard refreshes rely on periodic manual updates
* Limited historical data may impact trend accuracy and forecasting
* Product categorization assumptions may need validation from the product team

---

## 📞 **Interact with the Dashboard**

You can explore and interact with the full Power BI dashboard here:

👉 [**Click to View the Dashboard**](https://universityoflagos-my.sharepoint.com/:u:/g/personal/180205152_live_unilag_edu_ng/ETlh1aFc4Z9Psy_nWV-9wksBr3Uv90efkuIA6yfm1-q7AQ?e=uukfB0)

---

## 🎮 **Case Studies & Business Impact**

* Identified bottlenecks in the sales cycle that led to restructured proposal workflows
* Improved enterprise deal targeting strategy based on revenue concentration insights
* Enabled sales manager to track reps’ performance and implement goal-based incentives

---

## 🎬 **Video Tutorials & Walkthroughs**

*Coming Soon – Comprehensive video walkthrough of the CRM Sales Opportunities Dashboard*

---

## ✍️ **Author**

**\[Your Name]** – Data Analyst | Power BI Developer | CRM Insights Strategist
🔗 \[LinkedIn] • \[Portfolio] • \[Email]

---

## 📌 **License**

This project is licensed under the MIT License – feel free to reuse with attribution.

---
