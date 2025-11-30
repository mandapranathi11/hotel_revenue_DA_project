
# Revenue Optimization Dashboard  
**Self-Learning Project | Power BI, Data Analytics, DAX**

An end-to-end revenue analytics project built using **Power BI** to analyze hotel performance across 30+ properties.  
The dashboard integrates 3 months of booking data and provides actionable insights into occupancy, pricing strategy, and revenue trends.

---

## Project Overview  
This project focuses on maximizing hotel revenue by analyzing booking patterns, room demand, pricing strategies, and property performance.  
Using Power BI, Power Query, and DAX, an interactive multi-page dashboard was developed to help hotel managers make data-driven decisions.

---

## Tech Stack  
| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Advanced KPIs & custom calculations |
| **Excel / CSV** | Raw booking dataset |

---

## Project Structure  
```

├── data/                 → Raw booking dataset
├── powerbi/              → Dashboard (.pbix file)
├── images/               → Dashboard screenshots
└── README.md

````

---

## Key Features  

### 1. End-to-End Data Flow  
- Cleaned & transformed 3 months of booking data  
- Standardized room types, dates, and revenue fields  
- Modeled relationship between properties, bookings, rates & demand  

---

### 2. Interactive Power BI Dashboard  
The dashboard contains multiple pages including:

#### 🔹 **Revenue Overview**
- Total revenue  
- RevPAR, ADR, Occupancy %  
- Revenue by property & room type  

#### 🔹 **Demand & Booking Trend Analysis**
- Daily & weekly booking trajectory  
- Cancellation impact  
- Seasonal patterns  

#### 🔹 **Pricing Strategy Review**
- Static vs dynamic pricing comparison  
- Underpriced & overpriced room categories  
- Rate distribution and revenue leakage  

---

### 3. Advanced DAX Measures  
Authored **25+** DAX measures including:

```DAX
ADR = DIVIDE([Total Revenue], [Total Rooms Sold])

RevPAR = DIVIDE([Total Revenue], [Total Available Rooms])

Occupancy % =
DIVIDE([Total Rooms Sold], [Total Available Rooms])

Revenue Uplift %
= ([Projected Dynamic Revenue] - [Actual Revenue]) / [Actual Revenue]
````

---

## Insights & Outcomes

* Identified **10–15% revenue uplift potential** by exposing inefficiencies in the static pricing strategy.
* Properties with high occupancy but low ADR indicated **underpricing**.
* Discovered **low-performing weekdays** where dynamic pricing could increase yield.
* Recommended optimal rate adjustments using demand-based pricing metrics.

---

## What I Learned

* Designing professional Power BI dashboards
* Writing advanced DAX for financial and operational metrics
* Understanding revenue management concepts: ADR, RevPAR, GOPPAR
* Turning raw booking data into business insights
* Improving pricing strategy using analytics

---
