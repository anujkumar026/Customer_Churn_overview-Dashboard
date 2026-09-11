# Customer_Churn_overview-Dashboard

# 📊 Customer Churn Overview Dashboard | Power BI

An interactive Power BI dashboard that analyzes customer churn patterns for a telecom-style business, identifying **who churns, why, and when** — enabling data-driven retention strategy.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 🎯 Objective

Customer churn directly impacts recurring revenue. The goal of this project was to build a self-service, interactive dashboard that helps a business:

- Quantify overall churn rate and its financial impact
- Identify the customer segments and behaviors most associated with churn
- Surface actionable levers (contract type, tenure, payment method) that the business can act on to reduce churn

This project simulates the kind of ad-hoc and recurring analysis a **Data / Business Analyst** would be asked to deliver to a retention or customer-success team.

---

## 🗂️ Dataset

- ~7,000 customer records with demographic, account, service, and billing attributes
- Key fields: `Contract Type`, `Tenure`, `Monthly Charges`, `Payment Method`, `Internet Service`, `Online Security`, `Churn` flag
- Cleaned and modeled in Power Query before building measures in DAX

---

## 🛠️ Tools & Skills Used

| Category | Tools / Techniques |
|---|---|
| Data Modeling | Power Query (data cleaning, transformation) |
| Analysis | DAX (calculated measures — Churn %, Avg Charges, Tenure Bands) |
| Visualization | Power BI (KPI cards, donut, bar, pie charts) |
| Interactivity | Slicers, drill-through, cross-filtering |
| Design | Custom dark theme, semantic color coding |

---

## 📈 Dashboard Preview

*(Add your exported dashboard screenshot here — drag the image into this repo and reference it below)*

```
![Dashboard Screenshot](assets/dashboard-preview.png)
```

---

## 🔍 Key Insights

1. **Contract type is the strongest churn driver.** Month-to-month customers churn at **44%**, roughly **4x higher** than two-year contract holders (**3%**) — suggesting long-term contracts significantly improve retention.

2. **New customers are the highest-risk segment.** Customers in their first **0–6 months** churn at **53%**, compared to just **17%** for customers with 12+ months of tenure — pointing to a critical early-onboarding retention gap.

3. **Churned customers pay more on average.** Customers who churned had an average monthly charge of **₹74.44**, vs **₹61.27** for retained customers — indicating price sensitivity may be a contributing factor to churn.

4. **Overall churn rate stands at 27%**, against an average monthly charge of **₹64.76** across the customer base — meaning over a quarter of the revenue base is currently at risk.

5. **Security and backup services correlate with retention.** Customers without online security/backup services show a different churn pattern compared to those with these add-ons, suggesting bundled services could be a retention lever.

> 💡 *Business takeaway: Prioritize retention efforts on month-to-month, newly onboarded (0–6 month) customers — this segment shows the highest combined risk.*

---

## 🚀 What This Project Demonstrates

- Translating raw transactional data into **decision-ready KPIs**
- Using **rate-based metrics (%) instead of raw counts** to avoid misleading conclusions
- Applying **semantic color design** (red = risk, green = retained) for faster stakeholder comprehension
- Building **interactive, filterable dashboards** rather than static reports

---

## 📁 Repository Structure

```
├── Customer_Churn_Dashboard.pbix   # Power BI source file
├── assets/                         # Dashboard screenshots
└── README.md
```

---

## 👤 About Me

**Anuj Kumar**
BCA Graduate | Aspiring Data / Business Analyst
📍 Mumbai, India

Skills: SQL · Power BI (DAX, Power Query) · Excel · Python (Pandas, NumPy, Matplotlib)

- 🔗 [LinkedIn](#)
- 🔗 [Portfolio / Other Projects](#)
- 📧 [Email](#)

---

⭐ *If you found this project useful or interesting, consider giving it a star!*# 📊 Customer Churn Overview Dashboard | Power BI

An interactive Power BI dashboard that analyzes customer churn patterns for a telecom-style business, identifying **who churns, why, and when** — enabling data-driven retention strategy.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 🎯 Objective

Customer churn directly impacts recurring revenue. The goal of this project was to build a self-service, interactive dashboard that helps a business:

- Quantify overall churn rate and its financial impact
- Identify the customer segments and behaviors most associated with churn
- Surface actionable levers (contract type, tenure, payment method) that the business can act on to reduce churn

This project simulates the kind of ad-hoc and recurring analysis a **Data / Business Analyst** would be asked to deliver to a retention or customer-success team.

---

## 🗂️ Dataset

- ~7,000 customer records with demographic, account, service, and billing attributes
- Key fields: `Contract Type`, `Tenure`, `Monthly Charges`, `Payment Method`, `Internet Service`, `Online Security`, `Churn` flag
- Cleaned and modeled in Power Query before building measures in DAX

---

## 🛠️ Tools & Skills Used

| Category | Tools / Techniques |
|---|---|
| Data Modeling | Power Query (data cleaning, transformation) |
| Analysis | DAX (calculated measures — Churn %, Avg Charges, Tenure Bands) |
| Visualization | Power BI (KPI cards, donut, bar, pie charts) |
| Interactivity | Slicers, drill-through, cross-filtering |
| Design | Custom dark theme, semantic color coding |

---

## 📈 Dashboard Preview

*(Add your exported dashboard screenshot here — drag the image into this repo and reference it below)*

```
![Dashboard Screenshot](assets/dashboard-preview.png)
```

---

## 🔍 Key Insights

1. **Contract type is the strongest churn driver.** Month-to-month customers churn at **44%**, roughly **4x higher** than two-year contract holders (**3%**) — suggesting long-term contracts significantly improve retention.

2. **New customers are the highest-risk segment.** Customers in their first **0–6 months** churn at **53%**, compared to just **17%** for customers with 12+ months of tenure — pointing to a critical early-onboarding retention gap.

3. **Churned customers pay more on average.** Customers who churned had an average monthly charge of **₹74.44**, vs **₹61.27** for retained customers — indicating price sensitivity may be a contributing factor to churn.

4. **Overall churn rate stands at 27%**, against an average monthly charge of **₹64.76** across the customer base — meaning over a quarter of the revenue base is currently at risk.

5. **Security and backup services correlate with retention.** Customers without online security/backup services show a different churn pattern compared to those with these add-ons, suggesting bundled services could be a retention lever.

> 💡 *Business takeaway: Prioritize retention efforts on month-to-month, newly onboarded (0–6 month) customers — this segment shows the highest combined risk.*

---

## 🚀 What This Project Demonstrates

- Translating raw transactional data into **decision-ready KPIs**
- Using **rate-based metrics (%) instead of raw counts** to avoid misleading conclusions
- Applying **semantic color design** (red = risk, green = retained) for faster stakeholder comprehension
- Building **interactive, filterable dashboards** rather than static reports

---

## 📁 Repository Structure

```
├── Customer_Churn_Dashboard.pbix   # Power BI source file
├── assets/                         # Dashboard screenshots
└── README.md
```

---

## 👤 About Me

**Anuj Kumar**
BCA Graduate | Aspiring Data / Business Analyst
📍 Mumbai, India

Skills: SQL · Power BI (DAX, Power Query) · Excel · Python (Pandas, NumPy, Matplotlib)

- 🔗 [LinkedIn](#)
- 🔗 [Portfolio / Other Projects](#)
- 📧 [Email](#)

---

⭐ *If you found this project useful or interesting, consider giving it a star!*# 📊 Customer Churn Overview Dashboard | Power BI

An interactive Power BI dashboard that analyzes customer churn patterns for a telecom-style business, identifying **who churns, why, and when** — enabling data-driven retention strategy.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 🎯 Objective

Customer churn directly impacts recurring revenue. The goal of this project was to build a self-service, interactive dashboard that helps a business:

- Quantify overall churn rate and its financial impact
- Identify the customer segments and behaviors most associated with churn
- Surface actionable levers (contract type, tenure, payment method) that the business can act on to reduce churn

This project simulates the kind of ad-hoc and recurring analysis a **Data / Business Analyst** would be asked to deliver to a retention or customer-success team.

---

## 🗂️ Dataset

- ~7,000 customer records with demographic, account, service, and billing attributes
- Key fields: `Contract Type`, `Tenure`, `Monthly Charges`, `Payment Method`, `Internet Service`, `Online Security`, `Churn` flag
- Cleaned and modeled in Power Query before building measures in DAX

---

## 🛠️ Tools & Skills Used

| Category | Tools / Techniques |
|---|---|
| Data Modeling | Power Query (data cleaning, transformation) |
| Analysis | DAX (calculated measures — Churn %, Avg Charges, Tenure Bands) |
| Visualization | Power BI (KPI cards, donut, bar, pie charts) |
| Interactivity | Slicers, drill-through, cross-filtering |
| Design | Custom dark theme, semantic color coding |

---

## 📈 Dashboard Preview

*(Add your exported dashboard screenshot here — drag the image into this repo and reference it below)*

```
![Dashboard Screenshot](assets/dashboard-preview.png)
```

---

## 🔍 Key Insights

1. **Contract type is the strongest churn driver.** Month-to-month customers churn at **44%**, roughly **4x higher** than two-year contract holders (**3%**) — suggesting long-term contracts significantly improve retention.

2. **New customers are the highest-risk segment.** Customers in their first **0–6 months** churn at **53%**, compared to just **17%** for customers with 12+ months of tenure — pointing to a critical early-onboarding retention gap.

3. **Churned customers pay more on average.** Customers who churned had an average monthly charge of **₹74.44**, vs **₹61.27** for retained customers — indicating price sensitivity may be a contributing factor to churn.

4. **Overall churn rate stands at 27%**, against an average monthly charge of **₹64.76** across the customer base — meaning over a quarter of the revenue base is currently at risk.

5. **Security and backup services correlate with retention.** Customers without online security/backup services show a different churn pattern compared to those with these add-ons, suggesting bundled services could be a retention lever.

> 💡 *Business takeaway: Prioritize retention efforts on month-to-month, newly onboarded (0–6 month) customers — this segment shows the highest combined risk.*

---

## 🚀 What This Project Demonstrates

- Translating raw transactional data into **decision-ready KPIs**
- Using **rate-based metrics (%) instead of raw counts** to avoid misleading conclusions
- Applying **semantic color design** (red = risk, green = retained) for faster stakeholder comprehension
- Building **interactive, filterable dashboards** rather than static reports

---

## 📁 Repository Structure

```
├── Customer_Churn_Dashboard.pbix   # Power BI source file
├── assets/                         # Dashboard screenshots
└── README.md
```

---

## 👤 About Me

**Anuj Kumar**
BCA Graduate | Aspiring Data / Business Analyst
📍 Mumbai, India

Skills: SQL · Power BI (DAX, Power Query) · Excel · Python (Pandas, NumPy, Matplotlib)


Linkdin - https://www.linkedin.com/in/anuj-kumar-ssm/

---

⭐ *If you found this project useful or interesting, consider giving it a star!*
