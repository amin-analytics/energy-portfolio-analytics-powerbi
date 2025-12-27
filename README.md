# Energy Portfolio Analytics – Capital Allocation & Risk Insights (Power BI)

## Project Overview
This project presents an executive-level energy portfolio analytics dashboard built in Power BI, designed to support capital allocation, risk assessment, and performance optimization across renewable energy investments.

The report simulates a real-world energy investment portfolio covering wind and solar projects across multiple regions, focusing on capacity, CAPEX exposure, IRR, and risk-adjusted performance.

## Business Objectives
- Monitor total portfolio capacity and capital exposure
- Evaluate development pipeline vs operational assets
- Assess risk concentration across regions and technologies
- Support investment prioritization using risk-adjusted metrics

## Key Metrics
- Total Portfolio Capacity (MW)
- Development Pipeline Capacity (MW)
- Total CAPEX Exposure (USD m)
- Weighted Average IRR (%)
- High-Risk Capacity Share (%)
- High-Risk CAPEX Share (%)


## Pages Included
### 1. Executive Energy Portfolio Overview
- Portfolio-wide KPIs for capacity, CAPEX, and IRR
- Capacity and CAPEX breakdown by region and technology
- Project status analysis (Pipeline, Committed, Operational)
- Interactive slicers for region, technology, and project status

### 2. Risk & Investment Exposure Analysis
- Development pipeline capacity by risk level
- CAPEX exposure split by risk category
- Risk-adjusted IRR analysis
- Identification of high-risk concentration areas

### 3. Performance Drivers – Region & Technology
- Heatmap showing IRR performance by region and technology
- Decomposition tree for capacity and IRR drivers
- Waterfall chart illustrating CAPEX contribution by region
- Context-aware KPIs responding to selected filters

## Business Questions Answered
- Where is capital most exposed to high-risk projects?
- Which regions and technologies drive portfolio returns?
- How balanced is the development pipeline across risk levels?
- Which investment areas offer the best risk-adjusted returns?

## Data Modeling & DAX
- Star schema with fact and dimension tables
- Dedicated Date, Region, Technology, Risk, and Status dimensions
- Measures for:
        - Weighted Average IRR
        - Development Pipeline Capacity
        - Risk-based CAPEX and capacity shares
        - Context-aware KPIs using CALCULATE and FILTER
- Clean one-to-many relationships following BI best practices

## Tools & Skills Demonstrated
- Power BI
- DAX (CALCULATE, FILTER, DIVIDE, context handling)
- Data modeling (investment-grade star schema)
- Executive dashboard design
- Energy & infrastructure analytics

## Screenshots
Screenshots of all pages are included in the `screenshots` folder for quick review. I have also uploaded all pages together as a PDF file for convenience.

## PBIX File Access
The Power BI (.pbix) file is available upon request for hiring managers and reviewers.

## Author
Amin,
Energy & Business Intelligence Analyst  
Helsinki, Finland  
📧 amin.analytics1@gmail.com
