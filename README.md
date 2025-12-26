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
- Contributed to completing the infographic that illustrates our insights in an easy and informative way.

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
- **Tableau Desktop** – Interactive dashboard design and visual analytics  
- **Tableau Prep Builder** – Data cleaning, transformation, and preparation    
- **Data Visualisation & Analytics** – KPI design, insight generation, and storytelling  
- **Procurement Analytics** – Cost savings, supplier risk, and performance analysis  

---

## Key Learnings
- Effective analytics requires more than charts because **clarity, usability, and context** are critical  
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

## How the Solution Addressed the Business Problems

The procurement analytics solution was designed to directly respond to the challenges identified by senior management: shrinking profit margins, limited visibility into supplier pricing, and growing supplier dependency risks.

### 1. Lack of Visibility into Procurement Spend
One of the core problems was the absence of a clear, executive-level view of where procurement money was being spent.

**How the dashboard helped:**
- The **KPI Monitoring & Executive Overview dashboard** consolidated total spend, average order value, supplier count, and seasonal trends into a single view.
- This immediately revealed that total procurement spend increased to **$11.5M in 2024 (+10% YoY)** while the number of suppliers remained fixed at 10, indicating growth on a narrow supplier base.
- Subcategory comparisons showed that although many items were purchased in high volumes, **spend was heavily concentrated in a small number of high-value items** such as frames, batteries, and displays.

**Impact:**  
Executives could quickly identify where procurement scale existed and which categories warranted closer scrutiny for negotiation and risk management.

---

### 2. Inconsistent Pricing and Cost Leakage
Management suspected that the same products were being purchased at different prices from different suppliers but lacked evidence to act on this.

**How the dashboard helped:**
- The **Cost Savings Analysis dashboard** introduced product-level price variance charts, allowing direct comparison of unit prices across suppliers.
- For example, the same frame products showed price gaps of **$160–$260 per unit** between suppliers.
- A **Total Potential Savings by Product chart** ranked items by savings impact, showing that just **five products accounted for nearly 49% of total savings potential**.

**Impact:**  
This transformed vague concerns into quantifiable insights, enabling procurement teams to:
- Set realistic **target prices**
- Prioritise negotiation on high-impact SKUs
- Capture savings without reducing purchase volumes or quality

---

### 3. Supplier Dependency and Supply Chain Risk
Another major concern was over-reliance on a small number of suppliers for critical components.

**How the dashboard helped:**
- The **Supplier Performance & Risk dashboard** visualised supplier concentration, showing that **63% of total spend was concentrated among the top five suppliers**.
- Drill-down views highlighted **single-sourced and high-dependency SKUs**, particularly in frames, drivetrain components, and e-bike electronics.
- The **Supplier Consolidation Matrix** clearly distinguished:
  - Categories with too many suppliers (opportunity for consolidation)
  - Categories with only one supplier (high continuity risk)

**Impact:**  
Executives could make informed decisions about:
- Where to consolidate suppliers to increase bargaining power
- Where to diversify suppliers to reduce disruption and pricing risk

---

### 4. Making Insights Actionable for Non-Technical Executives
Senior stakeholders were time-poor and not highly technical, so insights needed to be intuitive and decision-focused.

**How the dashboard helped:**
- Interactive filters, drill-downs, and navigation allowed users to move from **high-level KPIs to product- and supplier-level detail in seconds**.
- Selecting a single product dynamically updated price variance, supplier distribution, and savings metrics across the dashboard.
- Clear visual hierarchy ensured that key risks and opportunities stood out without requiring technical explanation.

**Impact:**  
The solution moved beyond reporting and enabled **direct action**, supporting decisions around supplier renegotiation, consolidation strategies, and long-term procurement planning.

---
## Key Insights from the Infographic

The infographic provides a concise, executive-level summary of the most critical procurement patterns identified in the analysis, reinforcing the findings from the dashboards.


[View the Infographic](./case_study_documentation/Case%20Study%20Analysis%20Infographic.pdf)


<img width="487" height="1222" alt="image" src="https://github.com/user-attachments/assets/99bccbf1-39be-4b26-b105-5775aa493fc8" />



### 1. Spend Is Highly Concentrated in a Few Product Categories
Procurement spend is heavily concentrated in a small number of high-value components.  
**Frames, Displays, and Batteries together account for approximately 49% of total procurement spend ($10.78M).**

**Insight:**  
This level of concentration means that even small pricing improvements or contract renegotiations in these categories could deliver **disproportionately large margin gains**. These products should be prioritised for strategic sourcing and supplier negotiations.

---

### 2. Cost-Saving Opportunities Are Declining but Still Material
Total potential savings declined from **$2.34M in 2023 to $1.73M in 2024 (–26%)**.

**Insight:**  
The reduction in savings potential reflects **narrower price gaps between suppliers**, suggesting increasing price consistency across key products. While this indicates a more mature procurement environment, it also signals that **future savings will require more targeted, strategic negotiation**, rather than relying on obvious price dispersion.

---

### 3. Extreme Supplier Dependency Increases Risk
Procurement spend is highly concentrated among a small group of suppliers.  
The **top five vendors account for approximately 63% of total spend in 2024**.

**Insight:**  
This dependency creates both leverage and vulnerability. While supplier concentration can improve bargaining power, it also exposes the business to **pricing shocks, delivery disruptions, and reduced negotiation flexibility** if a key supplier underperforms or exits.

---

### 4. Clear Seasonal Procurement Patterns Enable Strategic Timing
Procurement spending follows predictable seasonal cycles:
- **Spikes:** March–April and June–October  
- **Dips:** January–March and April–June  

**Insight:**  
These patterns create opportunities to **time supplier negotiations during quieter periods**, stabilise cash flow, and lock in favourable pricing ahead of peak demand periods.

---

### 5. Product-Level Price Variance Reveals Negotiation Leverage
The infographic highlights meaningful price differences for identical products across suppliers.  
For example, **Outback Engineering consistently offers the lowest prices for Carbon and Aluminium Gravel Frames**, while Sunstate Components is the most expensive, with unit price gaps of **$260 and $168 respectively**.

**Insight:**  
These price variances provide clear evidence to support:
- Target price setting  
- Supplier benchmarking  
- Standardisation of purchasing decisions  

Even modest per-unit differences can translate into **six-figure savings at scale**.

---





### Summary
By combining clean data preparation, KPI-driven dashboards, and intuitive interactivity, the solution converted thousands of procurement records into **clear, strategic insights**. The infographic reinforces that Velocipede Cycles’ procurement challenges are driven by **spend concentration, supplier dependency, and pricing inconsistency**. At the same time, it highlights actionable opportunities to improve margins through **focused negotiation, better supplier strategy, and timing decisions aligned with seasonal demand**.
This allowed Velocipede Cycles’ leadership team to identify inefficiencies, quantify savings opportunities, and proactively manage supplier risk, because our solution directly addresses the root causes of declining profit margins.

---

## Notes
- Academic group project completed as part of **INF20016 – Big Data Management**  
- Shared for **learning and portfolio purposes**  
- No real company, confidential, or proprietary data is included  

---

## License
This project is licensed under the **MIT License** and is shared for educational and portfolio use.
