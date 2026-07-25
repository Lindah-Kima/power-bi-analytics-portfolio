# 📊 Sales Performance Dashboard

An interactive Power BI report built to monitor sales performance across branches, products, and time. The dashboard provides a centralized view of key business metrics, helping users track trends, compare branch performance, and explore sales data through interactive visuals.

🔗 **Live Report:** [View Report](https://app.powerbi.com/view?r=eyJrIjoiMTA3MDYwZTMtYzcxYy00Nzk1LWEwOWYtMDdhMGFmYzQ2NjhjIiwidCI6IjMwMzQ4NTMyLTliZTktNDVmYy05ZTU0LTk3ZjQ0Y2U0ZGRjOSIsImMiOjl9)

---

# Project Workflow

```
Data Understanding
        ↓
Data Cleaning & Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Dashboard Design
```

---

## Dataset

A sales dataset containing transactional records, branch information, products, and order details.

Key fields include:

- Orders
- Sales Amount
- Products
- Branches
- Dates
- Customers

---

## Data Understanding

Before building the report, the dataset was explored to understand:

- Table relationships
- Business entities
- Missing values
- Data types
- Sales metrics required for reporting

This step helped define the KPIs and report structure before any modeling began.

---

## Data Preparation

Power Query was used to prepare the dataset by:

- Cleaning inconsistent values
- Renaming fields
- Correcting data types
- Removing unnecessary columns
- Creating analysis-ready tables

---

## Data Modeling

The report uses a relational data model designed to support efficient filtering and accurate calculations.

The model includes relationships between:

- Sales
- Products
- Branches
- Customers
- Calendar

---

## DAX

Custom measures were created to support business reporting, including:

- Total Sales
- Total Orders
- Average Order Value
- Monthly Sales
- Daily Sales
- Sales by Branch

---

## Dashboard

The report consists of three pages:

### Executive Overview

- Business KPIs
- Monthly Sales Trend
- Daily Sales Trend
- Branch Performance Summary

### Branch Performance

- Revenue by Branch
- Monthly Branch Comparison
- Sales Distribution

### Time Analysis

- Monthly Trends
- Daily Trends
- Quarter Analysis
- Interactive Date Filtering

---

## Repository Structure

```
retail-sales-performance
│
├── README.md
├── sales_performance.pbip
├── images
│   ├── executive_page.png
│   ├── branches_page.png
│   ├── time_analysis_page.png
│   └── data_model.png

```
---

## Dashboard Preview

### Executive Overview

![Executive Overview](images/executive-overview.png)

### Branch Performance

![Branch Performance](images/branch-performance.png)

### Time Analysis

![Time Analysis](images/time-analysis.png)

### Data Model

![Data Model](images/data-model.png)

---

## Tools

- Power BI Desktop
- Power Query
- DAX

---

## Connect

**LinkedIn:** https://www.linkedin.com/in/lindah-kima-mmboga