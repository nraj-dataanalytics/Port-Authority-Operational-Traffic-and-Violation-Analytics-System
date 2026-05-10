# Port Authority Operational Traffic and Violation Analytics System

## Project Overview

This repository contains the supporting technical work for the **Port Authority Traffic on Bridges and Tunnels** business analytics capstone project.

The project analyzes traffic usage, toll violations, congestion patterns, 2025 facility-level traffic shifts, and future facility usage forecasting across Port Authority bridge and tunnel facilities. The goal is to move beyond basic reporting and create a structured analytics system that helps decision-makers understand where traffic pressure is concentrated, when demand peaks, how violations behave, and how future usage can be monitored.

The final project includes a written management report, a Power BI dashboard, cleaned datasets, Python notebooks, and PDF exports of the analysis workflow.

---

## Business Problem

The Port Authority of New York and New Jersey manages critical bridge and tunnel infrastructure that keeps regional traffic moving. Traffic patterns are affected by facility location, seasonality, day-of-week behavior, weather, toll violations, vehicle composition, and potential changes in driver behavior.

This project was designed to answer the following business questions:

1. What are the top factors that affect usage of bridges and tunnels by drivers?
2. How many toll violations are there by time interval and facility?
3. What are the busiest times throughout the year, and how is traffic affected by seasonality, vehicle type, violations, weather, and time-based patterns?
4. Did 2025 traffic patterns shift across facilities, possibly indicating congestion or pricing-related route redistribution?
5. What is the forecasted future usage of facilities beyond 2025?

---

## Project Objectives

The main objectives of this project are to:

- Build a clean and integrated analytical dataset from multiple traffic-related sources.
- Identify the major drivers of facility usage.
- Quantify toll violations by facility and time period.
- Understand seasonal, weekly, and facility-specific traffic patterns.
- Evaluate 2025 traffic redistribution across facilities.
- Develop predictive and forecasting models using Python and AutoML.
- Present final insights through a management-focused Power BI dashboard.
- Provide clear, actionable recommendations for operational monitoring, automation, AI readiness, and future forecasting.

---

## Repository Structure

```text
Port-Authority-Operational-Traffic-and-Violation-Analytics-System/
│
├── README.md
│
├── notebooks/
│   ├── 01_data_audit.ipynb
│   ├── 02_descriptive_analysis_and_eda.ipynb
│   ├── 03_data_cleaning_grain_alignment_integration.ipynb
│   ├── 04_sampling.ipynb
│   ├── 05_model_development.ipynb
│   └── 06_model_implementation_python_appendix.ipynb
│
├── reports/
│   ├── 01_data_audit.pdf
│   ├── 02_descriptive_analysis_and_eda.pdf
│   ├── 03_data_cleaning_grain_alignment_integration.pdf
│   ├── 04_sampling.pdf
│   ├── 05_model_development.pdf
│   └── 06_model_implementation_python_appendix.pdf
│
└── PowerBI/
|   └── dashboard_screenshots_or_powerbi_link.txt
│   └── 06_model_implementation_python_appendix.pdf
│
└── Presentation
