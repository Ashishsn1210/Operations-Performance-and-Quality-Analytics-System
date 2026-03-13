# Manufacturing Performance & Quality Analytics System

## Project Overview
This project presents a Manufacturing Performance and Quality Analytics System developed using Google Looker Studio to monitor production performance and analyze quality rejection across multiple manufacturing firewall stages.

The system combines two dashboards:
1. Business Enabler Value Report (BEVR) – High-level operational monitoring used by management.
2. Quality Rejection Analytics Dashboard – Detailed rejection analysis to identify root causes.

Together, these dashboards provide both Operational performance monitoring and Root cause analysis of rejection

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
### 1. Business Performance Monitoring Dashboard
Provides a high-level operational overview of production and rejection across firewall stages.

### 2. Quality Rejection Analytics Dashboard
Provides detailed analysis of rejection drivers, including parts, defect types, and tonnage impact.

## Dashboard Modules
### Module 1 — Business Enabler Value Report (BEVR)
The BEVR dashboard provides a management-level view of manufacturing performance.

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

### Module 2 — Quality Rejection Analytics Dashboard
This dashboard focuses on deep analysis of rejection drivers.

Each phase dashboard includes the following KPIs:
- Total Production
- Rejection Value
- Rejection Quantity
- Rejection Rate %

Purpose: To identify high-impact rejection drivers so that quality teams can focus their root cause analysis on Critical defect types, High-rejection parts, and Phases contributing to major financial loss

Tonnage Rejection Analysis
In addition to quantity and value analysis, the dashboard also analyzes rejection based on tonnage.
This helps identify material loss caused by rejected parts, which is important for Raw material cost control, Production efficiency, and Waste reduction initiatives.

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
