# global-business-etl-star-schema

# Global Business ETL & Star Schema Project

ETL pipeline in Python with star schema modeling and Power BI dashboards for global business financials.

## 📌 Project Overview
This project demonstrates how to:
- Extract data from Google BigQuery
- Transform data in Jupyter Notebook using Python (Pandas)
- Build a star schema (fact + dimension tables)
- Visualize schema with NetworkX + Matplotlib
- Load outputs into Power BI for dashboards

## 📊 Schema Diagram
![Star Schema](schema_diagram.png)

## 📂 Repository Contents
- `etl_pipeline.ipynb` → Jupyter Notebook with ETL + schema code
- `fact_financials.csv` → Fact table
- `dim_company.csv` → Company dimension
- `dim_industry.csv` → Industry dimension
- `dim_headquarters.csv` → Headquarters dimension
- `schema_diagram.png` → Star schema visualization
- `requirements.txt` → Python dependencies

## 🚀 How to Run
1. Clone repo
2. Install requirements: `pip install -r requirements.txt`
3. Run `etl_pipeline.ipynb` in Jupyter
4. Import CSV outputs into Power BI for dashboards

## 🛠️ Skills Demonstrated
- Python (Pandas, Matplotlib, NetworkX)
- Google BigQuery
- Data Modeling (Star Schema)
- Power BI Visualization




Data engineering project: BigQuery → Jupyter → Star Schema → Power BI

Highlights
Project overview → what the ETL does, dataset source (BigQuery/Kaggle).

Schema design → explain fact + dimensions, include diagram.

How to run → steps to install requirements and run notebook.

Outputs → CSVs, Power BI dashboards.

Skills demonstrated → Python, Pandas, BigQuery, Data Modeling, Visualization, Power BI.
