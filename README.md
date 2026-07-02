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

**Key Energy and Sustainability Insights

Oil-rich economies remain highly carbon intensive. The top 6 per-capita emitters are all oil producers, and high-income oil economies such as Qatar, Bahrain, Kuwait, and Saudi Arabia emit about 555,152 tonnes of CO₂ per $1 billion GDP, around 2.3x more CO₂ per dollar of GDP than the average and about 1.8x less energy-efficient than non-oil countries.

Renewable energy remains extremely low in some oil exporters. These countries average only 0.3% renewable energy share, which is about 100x lower than the global average of 30%, despite having strong solar potential.

Qatar is an extreme outlier. Qatar emits about 620x more CO₂ per person than Burundi and roughly 12x the global average, reflecting LNG production, aluminum, cooling demand, and subsidized domestic energy.

Norway shows a different path. Norway achieves more than 60% renewable domestic energy, mostly hydroelectric, while maintaining world-leading GDP per capita, and its per-capita emissions are about 3.7x lower than the average of the Gulf oil countries.

Global emissions are highly concentrated. China, the US, and India account for 63.7% of global CO₂ emissions while producing 51% of global GDP and holding a large share of the world’s population.

High-income countries dominate economic output. They generate about 64.4% of global GDP with only 17.4% of the population, while low-income countries hold 9.4% of the population but generate only 0.5% of GDP.

Energy use rises sharply with income. A person in a high-income country consumes about 79x more energy than someone in a low-income country.

Some countries show a sustainable growth path. Uruguay, Paraguay, Guatemala, and Brazil combine development with relatively high renewable shares, around 57.8%, 58.8%, 62.1%, and 46.5% respectively.

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


