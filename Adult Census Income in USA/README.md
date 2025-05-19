
---

# 📦 Adult Census Income in USA – Data Analysis Project

---

## 📌 Table of Contents

1. [📊 Project Overview](#-project-overview)
2. [📌 Business Use Case](#-business-use-case)
3. [📂 Data Sources](#-data-sources)
4. [🛠 Tools & Technologies](#-tools--technologies)
5. [📈 KPIs Monitored](#-kpis-monitored)
6. [🧹 Data Cleaning](#-data-cleaning)
7. [📈 Key Insights](#-key-insights)
8. [🎯 Recommendations](#-recommendations)
9. [⚠️ Limitations](#-limitations)
10. [🎥 Video Tutorials & Walkthroughs](#-video-tutorials--walkthroughs)
11. [🚀 Future Improvements & Roadmap](#-future-improvements--roadmap)
12. [📊 Interact with the Dashboard](#-interact-with-the-dashboard)
13. [🖼️ Dashboard Preview](#-dashboard-preview)
14. [✍️ Author](#-author)
15. [📌 License](#-license)

---

## 📊 Project Overview

### 👥 Understanding Income Inequality in the U.S.

The **Adult Census Income in USA Dashboard** analyzes demographic and occupational patterns to predict whether an individual earns more or less than \$50,000 per year. Built for data-driven insights, this project explores socioeconomic trends across age, education, gender, marital status, and more.

It helps policymakers, social researchers, and businesses:

* Understand the demographics of high-income earners
* Identify inequalities based on gender, race, and education
* Support targeted social interventions and policies
* Guide business strategy for segmentation and targeting

---

## 📌 Business Use Case

This dashboard serves public policy analysts, HR managers, sociologists, and marketers to:

* **Segment Income Groups** based on demographics and job sectors
* **Evaluate Education & Income Link** for strategic education programs
* **Detect Gender or Racial Pay Gaps**
* **Support Policy Decisions** in workforce development and training

---

## 📂 Data Sources

* **UCI Machine Learning Repository – Adult Data Set**
  Fields include:
  `Age`, `Workclass`, `Education`, `Occupation`, `Marital Status`, `Race`, `Gender`, `Hours per Week`, `Native Country`, `Income`

---

## 🛠 Tools & Technologies

* **Microsoft Power BI**: Main tool for data visualization
* **Microsoft Excel**: Data preprocessing and exploration
* **Power Query**: Data analysis & EDA
* **Data Cleaning Techniques**: Ensured reliability for modeling and insights

---

## 📈 KPIs Monitored

| KPI                                      | Description                                     |
| ---------------------------------------- | ----------------------------------------------- |
| 👥 **Income Distribution**               | Share of people earning >\$50K vs. ≤\$50K       |
| 🎓 **Education Level vs Income**         | Income split across education tiers             |
| 👨‍👩‍👧‍👦 **Marital Status vs Income** | Influence of marital status on income           |
| 💼 **Occupation Insights**               | Highest/lowest income-generating job categories |
| 🕒 **Hours Worked vs Income**            | Weekly hours correlation with earnings          |
| 🌍 **Country & Race**                    | Income distribution by native country & race    |
| 🚻 **Gender Pay Gap**                    | Male vs Female income comparison                |

---

## 🧹 Data Cleaning

### Transformation Process:

1. **Removed Missing and Unknown Entries** in key fields (e.g., `Workclass`, `Occupation`, `Native Country`)
2. **Converted Categorical Variables** for analysis and modeling
3. **Standardized Field Names** for ease of reference
4. **Created Age Groups** for meaningful segmentation
5. **Filtered Outliers** in `hours-per-week` and `age`

---

## 📊 Dashboards Review Summary

### 🧍‍♂️🧍 Demographics Insights

#### 🔍 Key Insights

📉💰 **Majority of Adults Earn Below \$50K Annually**
A significant 76% of individuals earn less than \$50K annually, suggesting income inequality or a large segment of low-wage earners in the U.S. population. Only 24% surpass the \$50K mark, highlighting a potential economic imbalance.

👩👨‍🦳 **Seniors Dominate High Income Bracket While Young Adults and Adolescents Lag Behind**
Seniors have the highest representation among those earning above \$50K, while young adults and adolescents earn the least. This indicates income tends to grow with age and experience, but young workers may need targeted career acceleration support.

👩‍🦰👨 **Males Are More Likely to Earn Above \$50K Than Females**
While 46% of income earners are male, only 20% of females earn above \$50K, pointing to a clear gender income gap that persists in the U.S. workforce.

🌍🗽 **Naturalized Citizens and Refugees/Asylees More Likely to Earn Above \$50K Than Native-Born**
Naturalized Citizens (88%) and Refugees/Asylees (91%) have a higher proportion of high earners compared to Native-Born Citizens (74%), challenging common assumptions and emphasizing the economic contributions of immigrants.

💼📚 **Higher Educational Attainment Strongly Correlates With Higher Income**
Individuals with professional degrees, PhDs, and master’s degrees are overrepresented among high earners, whereas those with only high school or elementary education earn significantly less. Education remains a key determinant of income level.

#### 💡 Recommendations

📈🎯 **Invest in Upskilling & Education for Economic Mobility**
Since income correlates strongly with education, national and corporate upskilling programs (especially in tech, finance, and engineering) should be encouraged to help low-income groups move up the income ladder.

👩‍💼⚖️ **Address Gender Income Inequality**
Policies focused on pay transparency, female leadership, and return-to-work programs for women should be prioritized to reduce the income gap and promote gender equity.

🧑‍💻📚 **Support Young Adults With Entry-Level Career Acceleration**
Introduce mentorship, internships, and job placement programs tailored to adolescents and young adults to boost their earning potential earlier in their careers.

🌍🏅 **Leverage Immigrant Talent for Economic Growth**
Recognize and support the contributions of immigrants, especially naturalized citizens and refugees, by streamlining employment opportunities, validating foreign credentials, and removing systemic barriers.

📊📍 **Tailor Economic & Policy Interventions Based on Income & Citizenship Insights**
Since income varies by citizenship status, policymakers should design targeted interventions for Native-Born Citizens who are lagging, while also continuing to support immigrant success stories with enabling environments.

---

### 💼 Employment Insights

#### 🔍 Key Insights

🏛️👔 **Federal Government Jobs Provide Better Pay Compared to Local and Private Sector**
39% of federal employees earn above \$50K compared to only 21% of private-sector employees and none in internship or never-worked groups. Federal roles offer better financial rewards.

⌛🕔 **Higher Income Earners Work More Hours**
Individuals earning above \$50K work an average of 45 hours per week compared to 39 hours for lower earners, suggesting income is partly tied to labor intensity or job type.

👨‍💻📊 **Top Income-Generating Occupations Are Tech and Business Roles**
IT Managers, Software Engineers, Cybersecurity Analysts, and Business Analysts dominate the top-earning occupation list. These roles are future-proof, tech-driven, and high-demand.

🏭📈 **Technology Sector Outpaces Others in Income Distribution**
Among all sectors, the technology industry has the largest share of high-income earners, showing its dominance in driving economic value and personal wealth.

#### 💡 Recommendations

🏛️📝 **Promote Federal Government and Public Sector Employment Awareness**
Federal jobs offer better income potential. Governments and educators should highlight these opportunities during career counseling and public job fairs.

⏱️🧠 **Encourage Work-Life Balance Despite Higher Pay**
While more hours bring higher pay, employers must balance workload with employee wellness. Consider productivity-focused rather than hour-based performance rewards.

💻🚀 **Accelerate Tech Career Pathways Across All Age Groups**
The tech sector is a top-paying industry. Career pipelines—like coding bootcamps, tech apprenticeships, and certification programs—should be expanded to make these roles accessible to a broader population.

💼📊 **Promote Career Shifts Into High-Income Occupations**
Encourage reskilling programs for low-income workers to transition into high-paying roles like IT Management, Financial Analysis, or Cybersecurity—sectors with high income and future relevance.

---

## ⚠️ Limitations

1. **Historical Dataset** – Data is from 1994–1995; patterns may differ today
2. **Binary Income Threshold** – No granularity beyond >50K or <=50K
3. **Lacks Inflation or Cost-of-Living Adjustments**
4. **Missing Key Socioeconomic Indicators** – e.g., household size, region
5. **No Longitudinal Tracking** – Only a snapshot, no career trajectory data

---

## 🎥 Video Tutorials & Walkthroughs

### ▶️ Dashboard Walkthrough

📽️ *\[Coming Soon]* or link to YouTube walkthrough if available

### 🔧 Step-by-Step Breakdown

* Importing Dataset into Power BI
* Cleaning with Power Query
* Building Custom Measures (DAX)
* Designing an Interactive Income Insight Dashboard

---

## 🚀 Future Improvements & Roadmap

| Feature                            | Status    | ETA     |
| ---------------------------------- | --------- | ------- |
| Add Time-Series Tracking           | ⬜ Planned | Q3 2025 |
| Include Household Demographics     | ⬜ Planned | Q3 2025 |
| Predictive Income Modeling with ML | ⬜ Planned | Q4 2025 |
| Power BI Embedded Web App          | ⬜ Planned | Q4 2025 |
| Gender & Race Bias Analysis        | ⬜ Planned | 2026    |

---

## 📊 Interact with the Dashboard

📎 **[Click here to view the dashboard](https://universityoflagos-my.sharepoint.com/:u:/g/personal/180205152_live_unilag_edu_ng/EQ33EagtDpxBv2xyMo5fO3wByadzN0Cuc-sNHkx4j3ey2w?e=gfmRcY)**

---

## 🖼️ Dashboard Preview

### Demographic Insights

![Demographics Insights](https://github.com/user-attachments/assets/7e582d95-57d1-4667-ada6-fccf97106983)


### Employment Insights

![Employment Insights](https://github.com/user-attachments/assets/737641d6-38fa-44f0-b930-1e9360cf4d82)


---

## ✍️ Author

**Oladosu Ibrahim Adeniyi**
*Data Analyst | Financial & Cloud Enthusiast | Founder/CEO, CodeSphere Nexus Ltd.*

📧 **Email**: [oladosuadeniyi39@gmail.com](mailto:oladosuadeniyi39@gmail.com)
🔗 **LinkedIn**: [linkedin.com/in/oladosu-ibrahim-12427b197](https://www.linkedin.com/in/oladosu-ibrahim-12427b197)

---

## 📌 License

This project is licensed under the MIT License.

---

