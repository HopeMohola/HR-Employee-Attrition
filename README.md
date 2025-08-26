# Agent Performance Analysis
## Goal
The goal is to measure and visualize insurance agent performance across different dimensions (demographics, product sales, business growth, and customer retention) with an aim to identify top-performing agents, detect weak areas, and provide data-driven insights that can improve retention, sales strategies, and profitability.

## Dataset Overview
- **File:** Agent Performance Dataset
- **Records:** Insurance agency performance data across multiple years
- **Scope:** Includes agency identifiers, policy details, premiums, retention, claims, demographics, and sales channel activity.

## Key Metrics for Analysis
### 1. Business Growth
- New Business Premium (NB_WRTN_PREM_AMT)
- Total Written Premium (WRTN_PREM_AMT)
- 3-Year Growth Rate (GROWTH_RATE_3YR)
- New vs Renewal Mix

### 2. Customer Retention
- Retention Policies (RETENTION_POLY_QTY)
- Retention Ratio
- Churn Rate

### 3. Profitability & Risk
- Loss Ratio
- 3-Year Average Loss Ratio
- Premiums vs Claims Trend

### 4. Sales Activity
- Quotes vs Binds (Conversion Rate)
- Channel Performance (ELINKS, SBZ, eQT, etc.)
- Active Producers (Number of agents)

### 5. Demographics
- Customer Age Range (MIN_AGE, MAX_AGE)
- State-wise Performance (STATE_ABBR)
- Vendor-linked vs Non-vendor Agencies

### 6. Time-Based Trends
- Performance by Year (STAT_PROFILE_DATE_YEAR)
- Tenure of Agencies (AGENCY_APPOINTMENT_YEAR)

## Features in the Dataset(also included a data dictionary in my repo for convenience)
- **AGENCY_ID** – Unique number for each agency  
- **PRIMARY_AGENCY_ID** – Parent agency ID  
- **PROD_ABBR** – Short product code  
- **PROD_LINE** – Product type (Business/Personal)  
- **STATE_ABBR** – State abbreviation  
- **STAT_PROFILE_DATE_YEAR** – Year of record  
- **RETENTION_POLY_QTY** – Retained policies  
- **POLY_INFORCE_QTY** – Active policies  
- **PREV_POLY_INFORCE_QTY** – Active policies last year  
- **NB_WRTN_PREM_AMT** – Premium from new business  
- **WRTN_PREM_AMT** – Total premiums written  
- **PREV_WRTN_PREM_AMT** – Previous year’s premium  
- **PRD_ERND_PREM_AMT** – Earned premium in year  
- **PRD_INCRD_LOSSES_AMT** – Losses due to claims  
- **MONTHS** – Months in record  
- **RETENTION_RATIO** – Policy retention percentage  
- **LOSS_RATIO** – Losses ÷ Earned Premium  
- **LOSS_RATIO_3YR** – Average loss ratio (3 years)  
- **GROWTH_RATE_3YR** – Growth over 3 years  
- **AGENCY_APPOINTMENT_YEAR** – Year agency was appointed  
- **ACTIVE_PRODUCERS** – Number of sales agents  
- **MAX_AGE / MIN_AGE** – Age range of customers  
- **VENDOR_IND** – Linked to vendor (Yes/No)  
- **VENDOR** – Vendor name  
- **PL_START_YEAR / PL_END_YEAR** – Personal Lines data range  
- **COMMISIONS_START_YEAR / COMMISIONS_END_YEAR** – Commission data range  
- **CL_START_YEAR / CL_END_YEAR** – Commercial Lines data range  
- **ACTIVITY_NOTES_START_YEAR / ACTIVITY_NOTES_END_YEAR** – Notes data range  
- **CL_BOUND/QUO_*** – Commercial policies sold/quoted (MDS, SBZ, eQT)  
- **PL_BOUND/QUO_*** – Personal policies sold/quoted (ELINKS, PLRANK, eQTte, APPLIED, TransactNow)  

## Deliverables
- **Excel Dashboard** with:  
  - KPI Summary Cards (Retention, Growth, Loss Ratio)  
  - Trend Charts (Yearly Premiums, Claims vs Premiums)  
  - Funnel (Quotes → Binds)  
  - State Heat Map  
  - Demographic Slicer (Age, Vendor)  

- **Data Dictionary** (Excel file)  
- **README file** (this document)

## Expected Insights
- Which agents and states drive the most growth  
- Which products are profitable vs risky  
- How retention and churn vary across agents  
- Conversion rates across sales channels  
- Impact of demographics (age, vendor, state) on performance  

## Tools
- **Excel** (PivotTables, PivotCharts, Slicers, Power Query, Conditional Formatting)   

## Author
Prepared by: *Motshabi Hope Mohola*  
Email Address: motshabimohola@gmail.com

## Comments
Hope : I would really appreciate any feedback you might have, good or bad. I am open to constructive criticism but I am hoping that you are going to have fun working with the dataset just as I did. This was challenging but mostly fun for me and I hope the visuals are just as informing as they are cute. Check out more of my work.
