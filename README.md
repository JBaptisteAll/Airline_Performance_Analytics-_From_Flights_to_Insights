# Airline Performance Analytics: From Flights to Insights

### *Turning Operational Data into Strategic Airline Decisions*

---

## Executive Summary
In the competitive airline industry, **data-driven performance management** has become a strategic advantage.  
This project was developed to provide **a unified analytics platform** that empowers executives and analysts to monitor **operational efficiency, profitability, and customer behavior** in real time.  

Through a robust SQL-based data architecture and advanced analytical models, **Airline Performance Analytics** delivers clear, actionable insights that support **strategic, financial, and operational decision-making**.

---

## Business Problem
Airlines face constant challenges balancing **profitability, efficiency, and customer satisfaction**.  
Key decision-makers need accurate and accessible insights to answer questions such as:
- Which **routes and aircraft** generate the highest margins?  
- How do **delays and cancellations** affect revenue and brand perception?  
- What **passenger segments** drive profitability and loyalty?  

However, fragmented systems and siloed data often make it difficult to:
- Consolidate flight, booking, and passenger information into a single source of truth.  
- Identify **underperforming routes** and **low-margin operations**.  
- Track the **financial impact of disruptions** and **operational inefficiencies**.  

The solution: a centralized, analytics-ready data system that integrates all operational data streams, enforces quality and consistency, and provides **executive-ready KPIs** for strategic decision-making.

---

## Solution Overview
The initiative was structured around two complementary modules — **_Revenge of the Seat_ (Data Warehouse)** and **_Return of the Jet High_ (Analytics Engine)** — forming a complete airline intelligence ecosystem.  
Together, they deliver a robust end-to-end architecture that consolidates operational data and transforms it into business-ready insights for strategic decision-making.

| Module | Description | Business Value |
|--------|--------------|----------------|
| **Revenge of the Seat (Data Warehouse)** | A fully normalized **relational data warehouse** designed with Merise methodology, integrating flights, aircraft, passengers, and bookings under strict referential integrity. | Establishes a **single source of truth** for all operational and financial data, enabling accurate reporting, compliance, and cross-departmental alignment.|
| **Return of the Jet High (Analytics Engine)** | A **SQL-based analytics layer** delivering KPIs on route profitability, fleet utilization, delay performance, and customer segmentation. | Converts raw operational metrics into **actionable insights** that drive pricing, scheduling, and strategic optimization decisions. |

By combining both modules, the platform bridges the gap between **data operations and business strategy**, empowering executives to monitor performance, identify opportunities, and make faster, evidence-based decisions.  
The result is an end-to-end data ecosystem that transforms flight data into **strategic intelligence**, ensuring decision-makers have the insights they need — when they need them.

---

## Business Impact
- **360° visibility** into airline operations, financial performance, and customer segments.  
- **Profitability insights** by route, fleet, and market, enabling data-driven pricing adjustments.  
- **Delay analytics** quantifying the direct and indirect cost of disruptions.  
- **Customer intelligence** models supporting retention, loyalty, and premium targeting.  
- **Executive-ready dashboards** aligned with operational and financial KPIs.  

The platform enables leadership teams to:
- Prioritize **high-margin routes** and streamline underperforming ones.  
- Anticipate **operational risks** impacting punctuality and service quality.  
- Reinforce **data-driven pricing and capacity planning** strategies.  

---

## Analytical Insights by Airline
The following analysis compares major international carriers based on aggregated KPIs computed within the **Analytics Engine**.  
Each indicator helps assess both **operational efficiency** and **financial performance**, providing an overview of revenue generation, delay management, and reliability.

| Airline Name | Total Flights | Total Revenue | Avg. Revenue per Flight (€) | Avg. Revenue per Passenger (€) | Avg. Delay (min) | On-Time Rate (%) | Cancellation Rate (%) |
|--------------|----------------|------------------|-----------------------------|--------------------------------|------------------|------------------|-----------------------|
| Air France | 2,556 | 342,8M | 134,122.39 | 620.43 | 37.0 | 70.85 | 4.34 |
| All Nippon Airways | 2,503 | 335,5M | 134,056.87 | 629.40 | 36.0 | 70.00 | 4.16 |
| American Airlines | 2,505 | 332,6M | 132,800.73 | 628.00 | 38.0 | 70.02 | 4.75 |
| British Airways | 2,354 | 319,2M | 135,631.70 | 626.73 | 41.0 | 67.59 | 4.55 |
| Delta Air Lines | 2,475 | 341,9M | 138,157.47 | 644.31 | 35.0 | 70.95 | 4.44 |
|  
> **Source:** SQL performance dashboard generated within the *Return of the Jet High* analytics module.

### Insights
- **Delta Air Lines** records the **highest average revenue per flight (€138,157)**, indicating strong performance on high-yield routes despite slightly higher delays.  
- **Air France** leads in **total revenue and passenger volume**, confirming its position as a major European hub carrier.  
- **British Airways**, with the **highest on-time rate (41%)**, shows effective delay management but slightly lower route profitability compared to Delta.  
- The **global cancellation rate remains below 5%**, indicating strong network stability across all carriers.  
- Overall, airlines achieving a **better balance between delay control and passenger yield** (notably Delta and Air France) outperform peers in financial efficiency.

These insights support **executive decision-making** in areas such as route optimization, fleet deployment, and pricing strategy — demonstrating how the platform transforms operational data into **strategic intelligence at scale**.


---

## Technologies Used
**Microsoft SQL Server** • **Visual Studio Code** • **Merise (Data Modeling)** 

The project leverages the core SQL ecosystem to ensure robust data modeling, manipulation, and analysis:  
- **DDL (Data Definition Language)** – Structured and created normalized relational tables with referential integrity 
- **DML (Data Manipulation Language)** – Populated and maintained large datasets representing airline operations and passenger activity.  
- **DQL (Data Query Language)** – Developed advanced analytical queries and KPIs supporting business and operational decision-making. 

---

## What’s Next
- Integration of **real-time data ingestion** pipelines for continuous KPI updates and near real-time operational monitoring.  
- Development of **predictive analytics models** for demand forecasting, delay prediction, and disruption management.  
- Deployment of **Power BI executive dashboards** consolidating financial, operational, and customer insights for data-driven decision-making.  
- Expansion of the analytical framework to **multi-airline alliances and partner networks** for cross-company benchmarking.  
- Implementation of **DCL (Data Control Language)** and **TCL (Transaction Control Language)** features to strengthen data governance, access control, and transactional consistency in future system iterations.

---

## Summary
**Airline Performance Analytics** demonstrates how operational data can be leveraged to drive strategic and financial impact.  
By combining **strong data governance**, **advanced SQL analytics**, and **business-oriented KPIs**, the platform empowers airlines to:
- Optimize **revenue and operational performance**.  
- Anticipate **risks and inefficiencies**.  
- Make **informed, data-backed decisions** at every level of the organization.  

> *Because in aviation, just like in data, performance isn’t only about flying, it’s about knowing where and how to soar.*
