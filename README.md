# Flood Monitoring & Forecasting - Data Lakehouse & DW

Decision-support system for hydrological and flood risk monitoring developed for the Mondego river basin.

## Project Overview
* **Architecture:** Medallion Data Lakehouse (Bronze -> Silver -> Gold layers).
* **Dimensional Modeling:** Constellation / Galaxy Schema with 3 Fact tables (`Fact_Medicoes`, `Fact_Indicadores`, `Fact_Evento_Cheia`) and conformed dimensions (`Tempo`, `Estacao`, `Localizacao`, `Variavel`).
* **ETL Pipeline:** Built with SQL Server Integration Services (SSIS) & Microsoft SQL Server.
* **Visualization & BI:** Executive and operational decision-support dashboards built in Power BI.
* **Predictive Modeling:** Machine Learning models in Python (Random Forest with 88% recall) predicting flood alert risk within a 24-hour horizon.

## Full Report
The complete project documentation and analytical validation can be found in [`docs/PSDW.pdf`](docs/PSDW.pdf).
