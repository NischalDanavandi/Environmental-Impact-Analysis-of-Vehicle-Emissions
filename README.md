<img width="1366" height="720" alt="recommendations" src="https://github.com/user-attachments/assets/b9a4a51a-1e1c-44a6-8fb3-6ef9f5b48b92" /># CO2 Emissions Analysis: Vehicle Fleet Sustainability Insights

A Power BI project analysing CO2 emissions across a 6,654-vehicle fleet to identify the strongest drivers of emissions and support data-driven sustainability decisions for policy makers and fleet managers.

---

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Methodology](#methodology)
- [Business Questions](#business-questions)
- [Key Findings](#key-findings)
- [Insights & Recommendations](#insights--recommendations)
- [Dashboard Preview](#dashboard-preview)
- [How to Use](#how-to-use)
- [Author](#author)

---

## Overview
This project investigates which vehicle characteristics — fuel type, powertrain, engine size, and transmission — have the greatest impact on CO2 emissions. Using Power BI's built-in AI visuals, the analysis moves beyond simple aggregation into root cause analysis, identifying not just *what* is happening but *why*.

## Problem Statement
Understanding which vehicle types contribute most to CO2 emissions is critical for policy makers and fleet managers looking to meet sustainability targets. Without a clear breakdown of emission drivers, decisions on fleet electrification, fuel policy, and procurement are made on assumption rather than evidence. This project set out to identify the key emission drivers across 6,654 vehicles and translate the findings into actionable recommendations.

## Dataset
- **Size:** 6,654 vehicle records
- **Fields:** Fuel type, powertrain, engine size, transmission, CO2 emissions, and related vehicle attributes
- **Granularity:** One row per vehicle

## Tools Used
- **Power BI Desktop** — dashboard build and modelling
- **Power BI AI Visuals:**
  - Key Influencers — statistically identifies which factors most affect CO2 output
  - Top Segments — surfaces the segments with the most distinct emissions behaviour
  - Decomposition Tree — enables interactive drill-down through emission drivers

## Methodology
1. Imported and cleaned the vehicle dataset in Power BI
2. Applied the **Key Influencers** visual to statistically rank which variables (fuel type, powertrain, engine size, transmission) most strongly predict higher or lower CO2 output
3. Used the **Top Segments** visual to identify vehicle groupings with unusually high or low emissions
4. Used the **Decomposition Tree** to interactively drill from total fleet emissions down through each contributing factor, confirming the root causes flagged by Key Influencers
5. Synthesised the outputs into a set of business-facing findings and recommendations

## Business Questions
- Which powertrain type contributes most to fleet-wide CO2 emissions?
- How much of an impact does switching from ICE to electric have on average emissions?
- Which fuel type accounts for the largest share of total emissions?
- Do Battery Electric Vehicles maintain low emissions regardless of engine size?
- Which combination of vehicle attributes represents the highest-emitting segment?

## Key Findings
- **ICE powertrain increases average CO2 by 35.71 units** compared to electric alternatives
- **Petrol vehicles contribute 51.2% of total fleet emissions** — the single largest share by fuel type
- **Battery Electric Vehicles achieve near-zero CO2 across all engine sizes**, showing that electrification neutralises engine size as an emissions factor entirely

## Insights & Recommendations
- **Powertrain matters more than any other single factor.** The 35.71-unit gap between ICE and electric vehicles makes powertrain the highest-leverage variable for emissions reduction — prioritize electrification over smaller efficiency tweaks elsewhere.
- **Petrol is the primary target for reduction efforts.** With just over half of total fleet emissions coming from petrol vehicles, phasing down or replacing this segment would have the single largest impact on overall fleet CO2.
- **Engine size stops being a relevant lever once a vehicle is electric.** For fleet managers, this means electrification removes the need to separately manage engine-size-related emissions policy for that portion of the fleet.
- **Recommendation:** Sequence fleet transition efforts by starting with high-mileage petrol/ICE segments, since this is where electrification will produce the largest measurable drop in total emissions.

## Dashboard Preview
<img width="1366" height="720" alt="fuel_distribution" src="https://github.com/user-attachments/assets/8bdef9ba-b97f-4388-9b0a-53d4524c51f6" />
<img width="1366" height="720" alt="emission_drivers_segment1" src="https://github.com/user-attachments/assets/982eaedb-641f-4e84-b9d6-5850c423a306" />
<img width="1366" height="720" alt="emission_drivers_overview" src="https://github.com/user-attachments/assets/5325985b-40ac-49f3-b15d-152574b52a36" />
<img width="1366" height="720" alt="emissions_breakdown" src="https://github.com/user-attachments/assets/4246bdaf-0a14-448d-84cb-8470b16b04ef" />
<img width="1366" height="720" alt="recommendations" src="https://github.com/user-attachments/assets/8840a630-6c15-4007-a343-d2d267638108" />







## How to Use
1. Clone this repository
2. Open `CO2-Emissions-Analysis.pbix` in Power BI Desktop
3. Explore the Key Influencers, Top Segments, and Decomposition Tree visuals interactively to trace emissions back to their drivers

## Author
**Nischal Danavandi**
