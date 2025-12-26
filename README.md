# Procurement Analytics Dashboard (Tableau)

## Overview
This repository contains an **interactive procurement analytics dashboard** developed as part of an **academic group project** for *INF20016 – Big Data Management* at Swinburne University.

The project analyses **2023–2024 procurement data** for a case-study company, *Velocipede Cycles*, with the goal of supporting **executive-level decision making** across cost savings, supplier risk, and procurement efficiency.

The final solution focuses on turning raw procurement data into **clear, actionable insights** through KPI-driven dashboards and intuitive interactivity.

> ⚠️ *Educational case study only — no real company or confidential data is used.*

---
## User Story
Velocipede Cycles is a highly successful and expanding Australian-based retail chain specialising in high-quality road, mountain, and gravel bikes, as well as premium components and accessories sourced from leading global brands. With **15 stores operating across major Australian cities**, the company has experienced strong year-on-year sales growth and established a competitive position within the cycling market.

Despite this success, a recent internal review revealed a concerning trend: **net profit margins are beginning to decline**, even as revenue continues to rise. Senior management, led by CEO Jane Smith and COO Mark Williams, suspects that the issue lies not in sales performance but in the **efficiency and visibility of the procurement process**.

Key challenges identified include:
- Limited visibility into pricing for high-value items such as carbon frames and electronic groupsets  
- Inconsistent pricing for identical products across different suppliers  
- Heavy reliance on a small number of key vendors, increasing supply chain risk  

Given the volume and complexity of purchasing transactions, the leadership team lacks the time and resources to manually analyse historical procurement data. As a result, a team of junior analysts was commissioned to conduct a **data-driven deep dive into two years of purchasing data**.

The objective of this project is to move beyond basic cost tracking and deliver **strategic procurement insights**. The final deliverable must be a **professional, visually compelling, and executive-ready dashboard**, designed for time-poor and non-technical stakeholders. Insights should directly support decisions around supplier negotiation, consolidation, diversification, and long-term profitability.

---

## Project Objectives
- Establish a **baseline view of procurement performance** using executive KPIs  
- Identify **cost-saving opportunities** at product and supplier level  
- Assess **supplier concentration and dependency risks**  
- Improve dashboard **usability and clarity** for non-technical stakeholders  

---

## Dashboards Included
The Tableau dashboards are organised into three main analytical views:

1. **KPI Monitoring & Executive Overview**  
   - Total spend and year-on-year growth  
   - Average order value trends  
   - Supplier concentration and spend distribution  
   - Seasonal procurement patterns  

2. **Cost Savings Analysis** *(Primary focus of my contribution)*  
   - Potential savings by product (SKU)  
   - Price variance across suppliers  
   - Identification of high-impact negotiation targets  
   - Interactive filtering to isolate products, suppliers, and categories  

3. **Supplier Risk & Consolidation Analysis**  
   - Supplier dependency and concentration metrics  
   - Single-sourced product exposure  
   - Opportunities for supplier consolidation vs diversification  

---

## My Contribution
This was a **group university project**. The original dashboard concept and overall structure were primarily designed by **Phuong Bao Minh Nguyen**.

My contributions focused on **extending the project beyond the original requirements**, particularly around usability and decision support:

- Designed **additional procurement KPIs** covering cost savings, supplier concentration, and risk exposure  
- Enhanced **dashboard UX** by adding interactive filters, drill-downs, and navigation elements  
- Significantly improved the **Cost Savings Analysis dashboard**, making insights more intuitive and executive-friendly  
- Refined dashboard layout and interactivity to better support **negotiation and strategic decision-making**  
- Learned **Tableau from scratch** and applied data visualisation and storytelling principles  

---

## Data Preparation & Quality
To ensure reliable insights, the project included structured data quality checks:

- Removal of duplicate transaction records  
- Referential integrity validation across procurement, product, supplier, and agent tables  
- Standardisation of column naming and identifier formats  
- Validation of value ranges, units of measure, and calculated fields  

A reproducible data preparation flow was used to support transparency and repeatability.

---

## Tools & Technologies
- **Tableau** – Dashboarding & interactivity  
- **SQL** – Data querying and aggregation  
- **Data Visualisation & Analytics**  
- **Procurement Analytics**  

---

## Key Learnings
- Effective analytics requires more than charts — **clarity, usability, and context** are critical  
- Dashboard interactivity plays a major role in supporting executive decision-making  
- Learning Tableau expanded my analytics skill set and encouraged **tool-agnostic thinking** about dashboard design  
- Comparing tools, I found **Power BI’s UX more intuitive for deep customisation**, but Tableau was a fun and valuable platform to learn  

---

## Dashboard Previews

### KPI Monitoring & Executive Overview
<img width="2387" height="1602" alt="db1" src="https://github.com/user-attachments/assets/2bc253bd-c1a2-4bf7-a1c9-a2e06238af0c" />


---

### Cost Savings Analysis Dashboard
<img width="2386" height="1530" alt="db2" src="https://github.com/user-attachments/assets/805b9c95-addd-4a59-816a-ea98d8690714" />

---

### Supplier Risk & Consolidation Analysis
<img width="2399" height="1585" alt="db3" src="https://github.com/user-attachments/assets/67ffa11e-7034-4a40-9b72-d789f7228dd9" />


---

## Notes
- Academic group project completed as part of **INF20016 – Big Data Management**  
- Shared for **learning and portfolio purposes**  
- No real company, confidential, or proprietary data is included  

---

## License
This project is licensed under the **MIT License** and is shared for educational and portfolio use.
