# Olist E-commerce Business Dashboard

An end-to-end analytics project built on the Olist Brazilian E-commerce dataset. The reporting layer is powered by a Medallion Architecture (Bronze, Silver, and Gold), where raw transactional data is transformed into a dimensional model that supports interactive Power BI reporting.

This repository focuses on the Power BI analytics layer of the project. The Executive Dashboard is complete, while Customer and Logistics dashboards are currently under development.

🔗 **Live Dashboard:** https://app.powerbi.com/view?r=eyJrIjoiOWQ4MTEzMDItZTBkNi00NzFiLWEwNDgtMTE4ZDBhYjY1Yjk1IiwidCI6IjMwMzQ4NTMyLTliZTktNDVmYy05ZTU0LTk3ZjQ0Y2U0ZGRjOSIsImMiOjl9

---

# Project Architecture

```
           Olist Public Dataset
                    │
                    ▼
        Bronze Layer (Raw Data)
                    │
                    ▼
 Silver Layer (Clean & Standardized Data)
                    │
                    ▼
 Gold Layer (Dimensional Model)
                    │
                    ▼
      Power BI Semantic Model
                    │
                    ▼
      Interactive Dashboards
```

---

# Technology Stack

- PostgreSQL (Aiven)
- DBeaver
- SQL
- Power BI Desktop
- Power Query
- DAX
- Power BI Service

---

# Data Pipeline

## Bronze Layer

The Bronze layer stores the original Olist datasets in PostgreSQL without business transformations. It serves as the project's source-of-truth layer and preserves the raw structure of the data.

## Silver Layer

The Silver layer prepares the data for analysis by applying cleaning and standardization processes, including:

- Data type corrections
- Missing value handling
- Duplicate removal
- Data quality validation
- Standardized business fields

## Gold Layer

The Gold layer follows a Kimball dimensional model, organizing the data into fact and dimension tables optimized for reporting and analytical queries. This layer serves as the data source for the Power BI semantic model.

---

# Executive Dashboard

The Executive Dashboard provides a high-level view of marketplace performance from **September 2016 to October 2018**.

### Key Metrics

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Active States

### Report Highlights

- Revenue Trend
- Orders by Weekday
- Top Product Categories by Revenue
- Top Product Categories by Orders
- Top Customer States
- Executive Insights
- Interactive filtering by reporting period and product category

---

# Dashboard Preview

![Executive Dashboard](images/executive-dashboard.png)

---

## Development Roadmap

| Phase | Status |
|-------|--------|
| Bronze Layer | Complete |
| Silver Layer | Complete |
| Gold Layer | Complete |
| Power BI Data Model | Complete |
| Executive Report | Complete |
| Customer Report | In Progress |
| Logistics Report | Planned |

---

# Repository Structure

```
olist-ecommerce-analytics-dashboard/
│
├── README.md
├── Olist Ecommerce Dashboard.pbip
├── images/
│   ├── executive_page.png
│   └── data_model.png
```