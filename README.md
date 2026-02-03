# Lapse-rates-on-pricing-project
Actuarial lapse experience investigation and assumption setting using multi-cohort policy data in Excel.

## Overview
This project performs a **lapse experience investigation** for an insurance product using ten years of historical policy data.  
The objective is to derive **duration-based lapse assumptions** suitable for use in actuarial cash-flow and valuation models.

The analysis is implemented in **Microsoft Excel** and follows standard actuarial experience-study methodology.

## Business Context
Accurate lapse assumptions are critical for:
- Policy liability valuation
- Cash-flow modeling
- Profit emergence analysis

This project supports the assumption-setting process by analysing historical lapse behaviour across multiple policy cohorts.

## Data Description
The investigation uses experience data from **01/01/2015 to 31/12/2024**, including:
- Monthly lapse counts (all years)
- Death/claim counts:
  - Monthly in year 1
  - Annual thereafter
- Policy inception data by monthly cohort

### Key Assumptions
- Uniform distribution of lapses and deaths within each period
- Uniform distribution of policy inceptions within each month
- Only two decrements considered: **lapse** and **mortality**


## Methodology

### 1) Policies In-Force Reconstruction
- Reconstructed policies in force by:
  - Inception month (cohort)
  - Policy duration
- Created a runoff view of the book over time

### 2) Data Validation Checks
Outlined and justified key data checks, including:
- Completeness and consistency of exposure data
- Reasonableness of lapse and mortality counts
- Cohort alignment across datasets
- Identification of anomalous patterns

### 3) Crude Lapse Rate Calculation
- Grouped:
  - Lapses by inception year
  - Deaths by inception year
  - Exposure by inception year and duration
- Calculated crude lapse rates using the **principle of correspondence**

### 4) Experience Averaging
- Computed average lapse rates by duration over:
  - Last 10 years
  - Last 5 years
  - Last 3 years
- Discussed trade-offs between:
  - Credibility
  - Responsiveness to recent experience

### 5) Assumption Analysis & Visualization
- Graphed lapse rates by policy duration
- Analysed the shape and trend of lapse behaviour
- Assessed the reasonableness of the resulting assumption pattern


## Results
- Successfully reconstructed multi-cohort policy exposures
- Derived duration-dependent crude lapse rates
- Identified stable lapse patterns across policy durations
- Produced lapse assumptions suitable for actuarial valuation models
- Demonstrated how assumption choice varies by experience window length


## Skills Demonstrated
- Actuarial experience investigations
- Survival and decrement modeling
- Exposure calculation using correspondence principles
- Assumption setting and validation
- Multi-cohort data analysis
- Professional Excel-based actuarial modeling

## Tools
- Microsoft Excel

