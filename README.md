# 👨‍💻 Retail Consumer Insights & Analytics Pipeline
This project represents a complete, production-grade, end-to-end data analytics workflow, designed to mirror the technical and strategic responsibilities of a professional Data Analyst. The architecture encompasses all critical stages of the data lifecycle, including data ingestion, programmatic data cleaning, relational database modeling, advanced analytical querying, interactive business intelligence, and stakeholder-facing financial reporting.

## 📌 Project Overview
The core objective of this project is to build an analytical ecosystem that transforms multi-channel (online vs. offline) raw consumer datasets into strategic business intelligence. The pipeline is designed to solve a critical enterprise challenge: understanding customer purchasing behavior to optimize marketing efficiency, maximize customer lifetime value (CLV), and improve brand retention.

The project lifecycle is executed across three major technical layers:
* **Data Pipeline & Wrangling (Python):** Programmatic programmatic ingestion, exploratory data analysis (EDA), structural anomaly handling, and data transformation.
* **Relational Database Analytics (SQL):** Schema design, transaction simulation, and advanced analytical querying utilizing CTEs and Window Functions to isolate consumer trends and behavioral drivers.
* **Interactive Business Intelligence (Power BI):** Developing a multi-page executive KPI dashboard driven by advanced DAX measures to enable data-driven decision-making.

---

## 🛠️ System Architecture & Workflow

### 1. Data Ingestion & Engineering (Python)
The data preprocessing pipeline is documented in the `/data_preparation/` directory:
* **Exploratory Data Analysis (EDA):** Leveraged **Pandas** and **NumPy** to evaluate raw data distributions, analyze data types, and check column correlation matrices.
* **Data Cleansing:** Programmatically handled structural anomalies, addressed missing attributes, and normalized text configurations.
* **Database Target Ingestion:** Established an automated connection pipeline to export the clean datasets into a relational SQL database environment.

### 2. Analytical Database Querying (SQL)
The database analytical scripts are located in the `/sql_analysis/` directory:
* Developed a structured relational schema to organize consumer tables.
* Engineered complex SQL scripts utilizing **Common Table Expressions (CTEs)** and **Window Functions** to extract business performance insights.
* Formulated queries to isolate target customer segments, evaluate promotional discount elasticity, track seasonal purchase distributions, and calculate customer repeat purchase rates.

### 3. Executive Business Intelligence (Power BI)
The visualization assets are maintained in the `/dashboards/` directory:
* Integrated the relational SQL database with Power BI to establish a clean relational data model.
* Engineered custom **DAX** measures to build dynamic, time-intelligent metrics (e.g., MoM revenue growth, average order value trend, and customer retention intervals).
* Developed a highly responsive user experience with drill-down filters to separate performance metrics across demographics and sales channels.

### 4. Stakeholder Strategy & Reporting
The final strategic assets are located in the `/reports/` directory:
* Translated complex technical metrics into a structured, executive-level case study report detailing the strategic impacts on inventory and marketing.
* Prepared a comprehensive data presentation designed to bridge the gap between technical data and non-technical business leaders to drive product strategy.

---

## 📂 Repository Structure
```text
├── data_preparation/       # Jupyter Notebooks detailing the Python ETL pipeline
├── sql_analysis/           # Optimized SQL production scripts (CTEs, Window Functions)
├── dashboards/             # Compiled Power BI (.pbix) dashboard models
└── reports/                # Final business problem analysis report and presentation slides
