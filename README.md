# Manufacturing Performance & Quality Analytics System

## Project Overview
This project presents a Manufacturing Performance and Quality Analytics System developed using Google Looker Studio to monitor production performance and analyze quality rejection across multiple manufacturing firewall stages.

The system combines two dashboards:
1. Operations Performance Monitoring – High-level operational monitoring used by management.
2. Quality Rejection Analytics – Detailed rejection analysis to identify root causes.

Together, these dashboards provide both
- Operational performance monitoring
- Root cause analysis of rejection

The dashboards were developed to help production teams, quality engineers, and functional heads quickly evaluate manufacturing performance and take data-driven decisions during review meetings.

## Business Problem
Manufacturing operations generate large amounts of production and quality data every day.
Before implementing these dashboards, rejection and production performance were primarily reviewed using multiple Excel sheets and manually compiled reports.

This created several challenges:
- Production and rejection data were scattered across multiple reports.
- Identifying high-rejection parts required manual analysis.
- Financial impact of defects was not immediately visible.
- Comparing rejection across firewall stages required manual calculations.
- Review meetings spent significant time interpreting spreadsheets rather than discussing corrective actions.

## Solution Overview
To address this problem, a two-layer manufacturing analytics system was developed using Looker Studio.

The solution includes:
### 1. Operations Performance Monitoring Dashboard
Provides a high-level operational overview of production and rejection across firewall stages.

### 2. Quality Rejection Analytics Dashboard
Provides detailed analysis of rejection drivers, including parts, defect types, and tonnage impact.

## Dashboard Modules
### Module 1 — Operations Intelligence Dashboard
The dashboard provides a management-level view of manufacturing performance.

Key Metrics Tracked across all Firewall stages:
- Produced Tonnage
- Rejected Tonnage
- Produced Value
- Rejected Value
- Produced Quantity
- Rejected Quantity
- Rejection %

These metrics allow management to quickly evaluate - Overall production performance, Quality loss across stages, and Financial impact of rejected parts.

Purpose: To provide functional heads and managers with a quick snapshot of manufacturing performance during review meetings. This helps teams quickly identify which firewall stage requires attention.

#### Dashboard Overview
![Operations_Intelligence_Dashboard](https://github.com/Ashishsn1210/Manufacturing-Performance-and-Quality-Analytics-System/blob/686f9e57dec7636e1791d5791197a78aa42c37f4/Dashboard_Images/Operations%20Intelligence%20Dashboard.pdf)

### Module 2 — Quality Rejection Analytics Dashboard
This dashboard focuses on deep analysis of rejection drivers.

Purpose: To identify high-impact rejection drivers so that quality teams can focus their root cause analysis on Critical defect types, High-rejection parts, and Phases contributing to major financial loss.

#### Dashboard Overview
#### Firewall-1 Rejection Analysis

The Firewall-1 dashboard analyzes rejection occurring at the F1 production stage, which represents the initial quality checkpoint in the manufacturing process. This dashboard helps identify defects introduced during the first stage of production.

This dashboard helps production and quality teams quickly identify:
- Parts with frequent rejection
- Defects introduced during early production stages
- Financial impact of early-stage quality issues

![Firewall-1](https://github.com/Ashishsn1210/Manufacturing-Performance-and-Quality-Analytics-System/blob/3632de74ce20e5d5b1ddab902d3b132265a16a8c/Dashboard_Images/Quality_Rej_F1.png)

#### Firewall-2 Rejection Analysis

The Firewall-2 dashboard focuses on rejection occurring at the F2 production stage, which represents the intermediate inspection checkpoint in the manufacturing process. This stage often reflects defects that pass the first inspection but are detected during subsequent processing or machining operations.

The Firewall 2 dashboard enables teams to:
- Identify parts that fail during intermediate processing
- Understand defect patterns emerging during machining or processing operations
- Evaluate the financial impact of mid-stage production defects

![Firewall-2](https://github.com/Ashishsn1210/Manufacturing-Performance-and-Quality-Analytics-System/blob/3632de74ce20e5d5b1ddab902d3b132265a16a8c/Dashboard_Images/Quality_Rej_F2.png)

#### Final Inspection (FI) Rejection Analysis

The Final Inspection dashboard analyzes rejection occurring during the final quality inspection stage before product dispatch.
This stage is critical because defects detected here represent quality issues that were not identified in earlier firewall stages.

This dashboard helps teams:
- Identify products failing during the final quality check
- Evaluate defects escaping earlier inspection stages
- Understand financial losses caused by late-stage rejection

![Final Inspection](https://github.com/Ashishsn1210/Manufacturing-Performance-and-Quality-Analytics-System/blob/3632de74ce20e5d5b1ddab902d3b132265a16a8c/Dashboard_Images/Quality_Rej_FI.png)

#### Rejection Tonnage Analysis

The Rejection Tonnage dashboard analyzes rejection based on material weight impact, rather than only quantity or financial value. In manufacturing environments where raw material costs are significant, tonnage-based analysis provides important insights into material loss due to rejected parts.

![Overall_Rej_Ton](https://github.com/Ashishsn1210/Manufacturing-Performance-and-Quality-Analytics-System/blob/3632de74ce20e5d5b1ddab902d3b132265a16a8c/Dashboard_Images/Overall_Rej_Ton.png)

## Business Impact
Before implementing these dashboards, production and rejection data were analyzed through manual spreadsheets and compiled reports.
This made it difficult to quickly identify rejection trends during operational meetings.
The implementation of the analytics dashboards created a centralized platform for monitoring production and quality performance.

Key Improvements
- Production and rejection data became easily accessible through visual dashboards
- High-rejection parts could be identified quickly
- Financial impact of defects became clearly visible
- Rejection performance across firewall stages could be compared easily

## Tools & Technologies Used
- Google Looker Studio – Dashboard development and data visualization
- Google Sheets / Excel – Data preparation and transformation
- Manufacturing production datasets – Source data for analytics

## Why This Project Matters
This project demonstrates how manufacturing production data can be transformed into actionable operational insights.

By combining performance monitoring with rejection analysis, the system allows manufacturing teams to move from
Manual spreadsheet analysis → Visual data-driven decision making.
