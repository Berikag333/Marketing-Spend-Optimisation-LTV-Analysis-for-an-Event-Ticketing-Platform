# Marketing-Spend-Optimisation-LTV-Analysis-for-an-Event-Ticketing-Platform
Analyse user behaviour, conversion timing, LTV, CAC and ROMI to optimise marketing budget allocation for Showz.

## Overview
This project analyses Showz (event ticketing) data to understand user behaviour, conversion, customer value (LTV), acquisition costs (CAC) and marketing ROI (ROMI). The goal is to recommend how to allocate marketing budget across acquisition sources.

## Data
- visits: sessions (Uid, Device, Start Ts, End Ts, Source Id)
- orders: purchases (Uid, Buy Ts, Revenue)
- costs: marketing spend (source_id, dt, costs)

## Key Questions
- Usage: DAU/WAU/MAU, sessions/day, session duration, retention
- Sales: time-to-first-purchase, orders/user, average order value, LTV
- Marketing: spend by source/time, CAC by source, ROMI by source

## Deliverables
- KPI tables and time series charts by device and source
- Cohort-style conversion timing analysis
- LTV, CAC and ROMI calculations
- Budget recommendations with justification

## Tech
Python, pandas, matplotlib/plotly, Jupyter Notebook
# Marketing Spend Optimisation & LTV Analysis — Showz

## Objective
Understand how customers use Showz, when they convert, what value they generate (LTV), and whether marketing spend pays back (CAC/ROMI).

## 1. Data Preparation
Load visits, orders, and costs. Convert timestamps to datetime and validate data types.

## 2. Usage KPIs (Visits)
- DAU / WAU / MAU
- Sessions per day
- Session duration
- Returning behaviour (retention/return rate)

## 3. Sales KPIs (Orders)
- Time to first purchase (conversion lag)
- Orders per user over time
- Average order value
- LTV (by cohort and/or source)

## 4. Marketing KPIs (Costs)
- Total spend over time and by source
- CAC by source
- ROMI by source over time/cohorts

## 5. Visuals
Charts showing KPI differences by device and acquisition source, and how they change over time.

## 6. Recommendations
Recommend investment by source based on LTV, CAC, ROMI, and conversion/retention patterns.

## Repository Structure
showz-marketing-roi-analysis/
├── notebooks/          # Analysis notebook
├── data/               # Source datasets
├── README.md
└── requirements.txt

## Author
**Erika González**  
MBA | Marketing & Data Analytics  
Focus areas: Marketing Intelligence, Customer Analytics, Business Strategy
