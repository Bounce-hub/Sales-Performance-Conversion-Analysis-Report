# Sales Performance & Conversion Analysis

Emerald Prime Properties Ltd

## Project Description

This project performs an end-to-end sales performance and conversion funnel analysis for Emerald Prime Properties Ltd using structured business data and Excel-based analytics.

The objective is to:

Quantify lead-to-client conversion efficiency

Evaluate individual sales representative performance

Compare regional and property-type demand

Identify bottlenecks in the sales pipeline

The output is an interactive KPI dashboard for management-level decision support.

# Problem Statement

Despite high lead generation volume, Emerald Prime Properties experiences:

Low conversion efficiency

Uneven performance across sales reps

Regional performance disparities

Limited visibility into property demand patterns

This analysis answers:

## Which operational factors are driving or limiting sales conversions?

# Data Schema

The dataset contains structured records with the following fields:

| Field         | Type        | Description                         |
| ------------- | ----------- | ----------------------------------- |
| lead_id       | Integer     | Unique identifier for each lead     |
| sales_rep     | Categorical | Assigned sales agent                |
| status        | Binary      | Client / Pending                    |
| region        | Categorical | Lagos, Rivers                       |
| property_type | Categorical | Residential, Commercial, Industrial |
| inspection    | Binary      | Yes / No                            |
| gender        | Categorical | Male, Female                        |

# Core KPIs

| Metric          | Formula                     | Value     |
| --------------- | --------------------------- | --------- |
| Total Leads     | COUNT(lead_id)              | **225**   |
| Total Clients   | COUNTIF(status = "Client")  | **100**   |
| Pending Leads   | COUNTIF(status = "Pending") | **125**   |
| Conversion Rate | Clients / Leads × 100       | **44.4%** |

# Analytical Insights

## Sales Rep Performance

Funmi and Chioma generated the highest lead volume.

Funmi also recorded the highest client conversions.

Ahmed recorded the lowest conversion count.

## Regional Distribution

| Region | Lead Share |
| ------ | ---------- |
| Lagos  | 50.8%      |
| Rivers | 35.5%      |

Lagos is the primary revenue-driving region.

# Conversion Drivers

Inspection vs Conversion

Conversion with inspection: 55%

Conversion without inspection: 11.1%

Inspection is a statistically strong conversion driver.

## Customer Demographics

| Gender | Share |
| ------ | ----- |
| Male   | 72.3% |
| Female | 21.8% |

## Property Demand

| Type        | Share |
| ----------- | ----- |
| Residential | 64.6% |
| Commercial  | 34.6% |
| Industrial  | 0%    |

Residential dominates transactional volume.

# Tech Stack

Microsoft Excel (Power Query, Pivot Tables, KPI formulas)

Dashboard Visualization (Slicers, Dynamic charts)

# Dashboard Visualization

https://github.com/Bounce-hub/Sales-Performance-Conversion-Analysis-Report/blob/main/Sales-Performance-Conversion-Analysis.jpeg

# Business Impact

This dashboard enables:

Real-time sales monitoring

Performance benchmarking across reps

Regional resource allocation

Conversion funnel optimization

# Author

Victory Chukwuemeka
Data Analyst 
LinkedIn: https://www.linkedin.com/in/victor-chukwuemeka-ba9275228/



