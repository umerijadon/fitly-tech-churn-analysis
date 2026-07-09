# fitly-tech-churn-analysis

## Project Overview
This project analyzes customer churn for **Fit.ly Tech**, a subscription-based fitness application experiencing increasing customer attrition over recent quarters.

The objective of the analysis was to:
- Identify the major drivers of customer churn
- Understand behavioral patterns linked to retention risk
- Evaluate customer engagement and support experience
- Develop KPIs for ongoing churn monitoring
- Provide actionable recommendations to improve customer retention

The project combined multiple operational datasets and applied business-focused analytical techniques using Python.

---

# Business Problem

Leadership identified rising customer churn as a critical business issue due to:
- Increasing customer acquisition costs
- Revenue pressure from subscriber loss
- Retention challenges impacting growth

The business lacked a unified understanding of:
- Which customers were most likely to churn
- How engagement influenced retention
- Whether customer support performance affected churn outcomes
- Which operational metrics leadership should monitor proactively

The goal of this analysis was to convert fragmented operational data into actionable retention insights.

---

# Datasets Used

## Account Information
Contains:
- Customer ID
- Email
- State
- Subscription Plan
- Plan List Price
- Churn Status

## Customer Support
Contains:
- Ticket Time
- User ID
- Support Channel
- Support Topic
- Resolution Time
- Ticket Status

## User Activity
Contains:
- Event Time
- User ID
- Event Type

---

# Data Validation & Cleaning

The datasets originated from multiple systems with inconsistent formatting and missing values.

Key cleaning and validation steps included:
- Standardizing column names and text formatting
- Converting invalid numeric and datetime fields
- Handling missing values
- Removing unusable records
- Validating customer identifiers
- Normalizing engagement and support categories
- Detecting inconsistent support records
- Creating structured customer-level datasets

The cleaned datasets were merged into a unified analytical model for churn analysis.

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Feature Engineering

Several analytical features were developed to improve churn analysis, including:

- Activity Event Counts
- Active Days
- Days Since Last Activity
- Ticket Counts
- Average Resolution Time
- Unresolved Ticket Counts
- Deletion Request Indicators
- Customer Risk Segments

Customer segmentation categories were also created based on:
- Activity volume
- Support volume
- Resolution time
- Retention risk level

---

# Key KPIs Developed

The following KPIs were developed for business monitoring:

- Overall Churn Rate
- At-Risk Customer Rate
- Average Activity Events
- Average Ticket Volume
- Average Resolution Time
- Customer Engagement Metrics

Primary KPI Recommendation:
> **At-Risk Customer Rate**

This metric identifies customers showing signs of churn risk based on inactivity and poor support experience.

---

# Exploratory Analysis Performed

The analysis explored:
- Churn by subscription plan
- Churn by engagement level
- Churn by support volume
- Churn by resolution time
- Activity versus support interaction patterns
- Customer risk segmentation

---

# Key Insights

## Low Engagement Strongly Correlated with Churn
Customers with low activity levels showed significantly higher churn rates.

## Support Experience Influenced Retention
Longer support resolution times were associated with increased churn risk.

## High Support Volume Indicated Retention Risk
Customers submitting multiple support tickets demonstrated elevated churn probability.

## Operational Risk Segments Were Identifiable
Certain customer groups consistently displayed behavioral signs associated with churn.

## Opportunity for Proactive Retention
The business could reduce churn by identifying at-risk users earlier and improving customer support responsiveness.

---

# Visualizations Included

The project includes:
- Customer Count by Plan
- User Activity Event Distribution
- Churn Rate by Plan
- Churn Rate by Activity Volume
- Churn Rate by Support Volume
- Churn Rate by Resolution Time
- Activity vs Support Scatter Analysis

---

# Recommendations

Based on the analysis, Fit.ly Tech should consider:

1. Improving customer engagement initiatives for low-activity users
2. Reducing support ticket resolution times
3. Building proactive churn-risk monitoring systems
4. Targeting at-risk customer segments with retention campaigns
5. Monitoring churn KPIs weekly to identify operational issues early

---

# Estimated Project Scale

- Analyzed thousands of customer activity and support records
- Built 7+ analytical visualizations
- Developed customer-level churn-risk segmentation
- Automated data cleaning and KPI reporting workflows
- Engineered customer engagement and support metrics

---

# Project Deliverables

This repository contains:
- Cleaned analytical datasets
- Python analysis notebook
- Business visualizations
- Executive presentation
- Written analytical report
- KPI summary tables
- Churn segmentation outputs

---

# Author

**Jadon Umeri**  
Data Analyst focused on customer analytics, business intelligence, churn reduction strategies, and data-driven decision-making.
