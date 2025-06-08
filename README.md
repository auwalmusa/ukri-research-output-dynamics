# 🏛️ UKRI Funding Insights Dashboard
<p align="center">
  <img src="./3dd52fb6-fdc5-4b69-a873-84b5a8a22756.png" />
</p>

---

## 📚 Project Background

The UKRI (UK Research and Innovation) dataset captures research funding data across different councils in the UK between 2015 and 2019. This dashboard provides an interactive visualization of funding applications, awards, success rates, and institutional collaborations — helping research leaders make strategic, data-driven decisions.

---

## 🎯 Business Objective

To deliver a strategic dashboard that enables:
- 💷 **Funding Trends Analysis** — How has funding evolved over time?
- 🧠 **Council Performance Insights** — Which councils have the highest success rates?
- 🏛️ **Institutional Collaboration Tracking** — Which organizations collaborate the most on funded projects?
- 📊 **Application and Award Statistics** — Total applied vs awarded funding amounts, application volumes, award counts.

The goal is to support universities and policymakers with actionable intelligence for research funding strategies.

---

## 💾 Data Source

- **Source**: UKRI Funding Data (2015–2019)
- **Fields Used**:
  - Funding Year (FY Decision Date)
  - UKRI Council
  - Grant Category
  - Number of Applications
  - Number of Awards
  - Amount Applied For
  - Amount Awarded
  - Award Rate by Number and Value
  - Organisation (Lead and Collaborating)

---

## 📊 Dashboard Overview

**Main Features:**
- 📈 **Line Chart**: Total Funding Awarded Over Time
- 🏛️ **Bar Chart**: Top Funding Councils by Amount Awarded
- 🧠 **Bar Chart**: Award Success Rates by Council
- 🧩 **Horizontal Bar Chart**: Top Collaboration Organizations
- 📄 **KPI Cards**: Total Applied Funding, Total Awarded Funding, Total Applications, Total Awards

Interactive slicers allow dynamic filtering by Council and Year.

---

## 🔑 Key Insights

- Research England leads all councils with the highest award success rate (75%).
- Total awarded funding steadily increased from £2bn in 2015 to over £3bn in 2018.
- University College London (UCL) is the most active collaborator based on collaboration count.
- Notable disparities in success rates across councils highlight opportunities for strategic focus.

---

## 🛠️ Tools Used

- **PostgreSQL** (Data Storage and SQL Querying)
- **Power BI Desktop** (Data Visualization & Dashboarding)
- **Power Query** (Data Cleaning & Transformation)
- **DAX** (Custom Measures and Calculations)

---

## 📎 How to View

- Download the `.pbix` file.
- Open using **Power BI Desktop**.
- Connect to the PostgreSQL database if needed.
- Interact with slicers to explore funding patterns dynamically.

---

🎯 **Outcome:**  
A dynamic dashboard enabling research leaders and universities to optimize funding strategies and collaborative research initiatives.

---

## 📂 Repository Structure

| File                             | Description                                 |
|----------------------------------|---------------------------------------------|
| `UKRI_Funding_Dashboard.pbix`    | Power BI Dashboard File                    |
| `README.md`                      | Project overview and explanation           |
| `grant_category.csv`             | Funding data by category and council        |
| `awards.csv`                     | Awarded funding by organization             |
| `awards_collaboration_details.csv`| Collaboration details for awarded projects |

---
