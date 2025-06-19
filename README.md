# Chicago & Dallas Food Inspection BI Dashboard

This project integrates food inspection datasets from the cities of Chicago and Dallas into a unified dimensional model. It builds end-to-end ETL pipelines and develops insightful Power BI dashboards to analyze public health trends and regulatory compliance.

## 🎯 Project Goals

- Integrate food inspection data from two cities with different schemas
- Clean and transform the data for analytical querying
- Provide visual insights on business types, violations, and geographic patterns

## 🛠️ Tools & Technologies

- Alteryx (Data cleaning, unpivoting, joining)
- ER/Studio (Dimensional modeling)
- Azure Data Factory (ETL orchestration)
- Snowflake (Cloud Data Warehouse)
- Power BI (Dashboard visualization)

## 📌 Business Insights Delivered

- What are the most common violation types?
- How does compliance vary by ZIP code or business type?
- What risk categories are most frequently cited?
- What are inspection patterns over time?

## 🧱 Data Model Highlights

- One central fact table: `FCT_INSPECTION`
- Multiple dimension tables: `DIM_LOCATION`, `DIM_DATE`, `DIM_BUSINESS`, `DIM_VIOLATION`, `DIM_RISK`
- A bridge table to resolve many-to-many between inspections and violations

## 📁 Project Structure

├── ADF_Pipelines/
├── Alteryx_Workflows/
├── ER_Studio_Model/
├── Snowflake_SQL/
├── PowerBI_Dashboard/
├── Data_Dictionary.xlsx
└── README.md

## 🌐 Visualizations Include

- Violation frequency by city, ZIP, and risk level
- Trend analysis of inspection outcomes
- Interactive maps for geospatial risk analysis
- Heatmaps by business category and location
