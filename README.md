# Global-Energy-Consumption-Sustainability-Analysis

An end-to-end data analytics project exploring how economic, demographic, and sustainability factors relate to national energy consumption and carbon emissions across 210+ countries.

**Tools**: Excel | SQL | Power Query | Power BI | MySQL | World Bank | Our World in Data | EIA

**Project Summary**

This project combines 7 public datasets from 3 international sources to build a unified analytical model of global energy and sustainability performance. 

It includes data cleaning, database design, feature engineering, exploratory analysis, regression analysis, and dashboard development in Excel and Power BI.

**Business Question**

How well do GDP, population, and sustainability indicators explain differences in energy consumption and carbon emissions across countries?

**What I Did**

Collected and integrated data from World Bank, Our World in Data, and EIA.
Cleaned and standardized country-level datasets.
Built a MySQL database to structure and validate the data.
Created 5 derived metrics to improve analysis:
  Energy consumption per capita
  CO₂ emissions per capita
  Carbon intensity
  Renewable energy share
  Income group classification
Performed exploratory analysis and regression modelling.
Built 2 interactive dashboards in Excel and Power BI.
Designed KPI tracking, slicers, filters, and country-level comparisons.

**Key Insights**

GDP per capita is positively associated with energy consumption.
Population density alone has limited explanatory power.
Carbon intensity varies significantly between countries with similar economic output.
Renewable energy adoption is often linked to lower carbon intensity.
Energy mix and industrial structure matter more than GDP alone when explaining emissions.

**Tools and Skills**

Data cleaning and transformation.
SQL querying, views, aggregations, and validation.
MySQL relational database design.
Power Query for ETL.
Feature engineering and metric development.
Regression analysis and scenario modelling.
Excel dashboard design.
Power BI dashboard development.
Data storytelling and insight communication.

**Impact**

This project demonstrates the ability to turn raw public datasets into a structured analytical solution that supports sustainability benchmarking and evidence-based decision-making.

**Challenges Solved**

Inconsistent country naming across datasets.
Missing values in developing-country records.
Different reporting years across sources.
Unit standardization and data harmonization.

**Repository Structure**

Global-Energy-Consumption-Sustainability-Analysis/
├── README.md
├── Data/
├── SQL/
├── Excel Dashboard/
├── Power BI/
├── Images/
└── Documentation/

**Future Improvements**

Add regression diagnostics and statistical testing.
Build the workflow in Python for automation and reproducibility.
Create an automated ETL pipeline.
Add forecasting for energy demand and emissions.
Include more sustainability indicators.
Deploy the solution in a cloud environment.


