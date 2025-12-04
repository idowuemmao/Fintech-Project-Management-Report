# 🚀 Fintech Project Management Performance Analytics Report

*Built with Power BI + ZoomCharts visuals*

## 📌 Overview

Fintech companies often manage multiple digital product development projects simultaneously — from tap-to-pay systems to digital wallets and online payment APIs. Controlling **budget**, **timelines**, and **resources** is critical for successful delivery.

This Power BI report analyzes real project delivery data to help PMOs and business leaders answer key questions:

* Are projects **on time** and **within budget**?
* Where are the **schedule delays** and **cost overruns**?
* Which departments and locations deliver **most efficiently**?
* How do **experience levels** and **hourly rates** impact cost performance?
* Which **task workflows** cause rework or hold-ups?

The report surfaces actionable insights that improve **delivery efficiency**, **resource utilization**, and **financial control** across the fintech project lifecycle.

---

## 📂 Dataset

The model connects 6 core tables:

| Table            | Type      | Key Insights                             |
| ---------------- | --------- | ---------------------------------------- |
| Dim_Projects     | Dimension | Budget, timeline, risk, completion level |
| Fact_Tasks       | Fact      | Hours performance & workflow status      |
| Fact_Milestones  | Fact      | Delivery progress & slippage points      |
| Dim_Employees    | Dimension | Skill level, cost rate, location         |
| Dim_Departments  | Dimension | Organizational performance               |
| Dim_CountryFlags | Dimension | Regional visual context                  |

> Relationships form a clean **Star Schema** enabling accurate drilling by Department → Role → Project → Milestone → Task.

---

## 📊 Key Performance Metrics

| KPI                          | What It Measures                             |
| ---------------------------- | -------------------------------------------- |
| Schedule Performance         | Time efficiency (planned vs actual duration) |
| Cost Performance Index (CPI) | Cost efficiency (earned value vs spend)      |
| Budget Variance %            | Financial control vs project plan            |
| Task Efficiency              | Planned vs actual hours utilization          |
| Milestone Completion %       | Execution progress & blockers                |
| Projects On-Time vs Delayed  | Delivery risk signals                        |

Color-coded measures automatically highlight performance hotspots.

---

## 🧭 Report Navigation (3 Interactive Pages)

### ⭐ Page 1 – Executive Dashboard

**Objective:** Identify top-level project health, spending gaps & risk exposure.
**Insights provided:**

* Planned vs Actual Budget by Department (drill to roles)
* Distribution of Projects by Risk Level / Status
* Timeline view of project starts, completion, and risk trend
* KPI Matrix showing:

  * Avg Day Delay
  * Avg Completion %
  * Budget Variance %
  * Milestones & Tasks Completed
  * Cost Performance Index for each project

💡 Supports **executive monitoring** & **prioritization of at-risk projects**.

<img width="1290" height="726" alt="Screenshot_66" src="https://github.com/user-attachments/assets/0cbc5105-865e-4780-acf6-3f0780defcf0" />

---

### 💼 Page 2 – Resource and Cost Analysis

**Objective:** Measure how talent investment translates into performance.
**Key visuals:**

* Labour cost vs Task Efficiency per department (drill to role)
* Cost distribution by Experience Level
* Monthly trend of planned vs actual cost performance
* Country-City matrix on staffing & financial outcomes

💡 Reveals **where workforce capacity is strong** vs **where rework drives cost escalation**.

<img width="1291" height="724" alt="Screenshot_67" src="https://github.com/user-attachments/assets/30557b5a-3f7c-4b01-9bb7-a944b3d6a65c" />

---

### 🧩 Page 3 – Operational Insights

**Objective:** Compare time performance vs financial efficiency.
**Visuals:**

* Schedule performance and utilization by country (drill-down)
* Task load by status / priority
* Planned vs Actual Task Hours monthly trend
* **Scatter Plot:** Task Efficiency vs Cost Performance Index by department (drill to role)

🎯 Identifies **high-performing teams** and **critical improvement targets**.

<img width="1289" height="724" alt="Screenshot_68" src="https://github.com/user-attachments/assets/01bb6c6d-5f67-41aa-a967-43392bbfaa86" />
---

## 🔍 Technology Used

* **Power BI Desktop**
* **ZoomCharts Drill Down Visuals**
* DAX for:

  * Efficiency KPIs
  * Earned-Value style cost indicators
  * Performance categorization & color logic
* Star Schema for scalable analytics

---

## 📈 Business Value Delivered

✔ Improves cost governance and project forecasting
✔ Detects bottlenecks early using task hours + status trends
✔ Aligns staffing strategy with high-return project areas
✔ Highlights operational best-practice regions / roles
✔ Enables PMOs to intervene **before delays become critical**

---

## ▶️ Interactivity Features

* Cross-filtering across visuals
* Drill-down: Department → Role → Project → Task
* Geographic mapping with tooltips
* Dynamic KPI tooltips & information overlays
* Report tooltips for milestone/task level storyline

---

## 🔗 How to Use

1. Open the `.pbix` file in Power BI Desktop (2024+ version recommended)
2. Refresh dataset if connected to a live source
3. Use filters (Department, City, Experience Level) to explore performance views
4. Hover/trend drill for deeper insight into cost & timeline behavior

---

## 🧠 Future Enhancements

* Predictive analytics for **delay / cost risk forecasting**
* Milestone dependency mapping
* Scenario simulation for **resource reallocation**
* Automated alert system using Dataflows + Power Automate

---

## 👤 Author

**Emmanuel Idowu**
Data Analyst | Power BI | SQL | Excel | Financial & Operational Analytics
📩 Connect: LinkedIn Profile or DM [HERE](https://www.linkedin.com/in/emmanuel-idowu-analyst/)
Check me on Youtube [HERE](https://www.youtube.com/@Emmy-The-Analyst)

---

## 🏷 Hashtags

`#PowerBI #Fintech #ZoomCharts #ProjectManagement #BusinessIntelligence #CPI #SchedulePerformance #DataAnalytics #PortfolioManagement #DataStorytelling`

---
