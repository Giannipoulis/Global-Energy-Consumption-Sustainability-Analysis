# Global-Energy-Consumption-Sustainability-Analysis

An end-to-end data analytics project exploring how economic, demographic, and sustainability factors relate to national energy consumption and carbon emissions across **210+ countries**.

**Tools**: Excel | SQL | Power Query | Power BI | MySQL | World Bank | Our World in Data | EIA

## Project Summary

This project combines **7 public datasets** from **3 international sources** to build a unified analytical model of global energy and sustainability performance. 

It includes data cleaning, database design, feature engineering, exploratory analysis, regression analysis, and dashboard development in Excel and Power BI.

**Interactive Power BI Dashboard**

![BI Dashboard](Global-Energy-Consumption-Sustainability-Analysis/Images/BI_Dashboard.png)

## Business Question

How well do GDP, population, and sustainability indicators explain differences in energy consumption and carbon emissions across countries?

**What I Did**

- Collected and integrated data from World Bank, Our World in Data, and EIA.
- Cleaned and standardized country-level datasets.
- Built a MySQL database to structure and validate the data.
- Created 5 derived metrics to improve analysis:
  - Energy consumption per capita
  - CO₂ emissions per capita
  - Carbon intensity
  - Renewable energy share
  - Income group classification
- Performed exploratory analysis and regression modelling.
- Built 2 interactive dashboards in Excel and Power BI.
- Designed KPI tracking, slicers, filters, and country-level comparisons.

**Data Architecture **

![Flow Diagram](Global-Energy-Consumption-Sustainability-Analysis/Images/Data_Flow_Diagram.png)

**Dashboard Development**

Designed and developed two executive dashboards comprising:
  •	8+ KPI cards 
  •	10+ interactive charts 
  •	Dynamic country selector 
  •	Income-group segmentation 
  •	Regression analysis 
  •	What-If scenario analysis 
  •	Executive summary panel


## Key Insights

- GDP per capita is positively associated with energy consumption.
- Population density alone has limited explanatory power.
- Carbon intensity varies significantly between countries with similar economic output.
- Renewable energy adoption is often linked to lower carbon intensity.
- Energy mix and industrial structure matter more than GDP alone when explaining emissions.

## Excel Executive Dashboard

![Excel Dashboard](Global-Energy-Consumption-Sustainability-Analysis/Images/Excel_Dashboard.png)

## Global Energy and Sustainability Insights
- Oil-rich economies remain highly carbon intensive. The top 6 per-capita emitters are all oil producers, and high-income oil economies such as Qatar, Bahrain, Kuwait, and Saudi Arabia emit about **555,152 tonnes of CO₂ per $1 billion GDP**, around **2.3x** more CO₂ per dollar of GDP than the global average, and about **1.8x** less energy-efficient than non-oil countries.
- Renewable energy remains extremely low in some oil exporters. These countries average only **0.3% renewable energy share**, around **100x lower** than the global average of **30%**, despite strong solar potential.
- Qatar is an extreme outlier. It emits about **620x more CO₂ per person than Burundi** and roughly **12x the global average**, reflecting LNG production, aluminum, cooling demand, and subsidized domestic energy.
- Norway shows a different path. It achieves more than **60% renewable domestic energy**, mostly hydroelectric, while maintaining world-leading GDP per capita, and its per-capita emissions are about **3.7x lower** than the average of the Gulf oil countries.
- Global emissions are highly concentrated. China, the US, and India account for **63.7% of global CO₂ emissions**.
- High-income countries dominate economic output. They generate about **64.4% of global GDP** with only **17.4% of the population**, while low-income countries hold **9.4% of the population** but generate only **0.5% of GDP**.
- Energy use rises sharply with income. A person in a high-income country consumes about **79x more energy** than someone in a low-income country.
- Some countries show a sustainable growth path. Uruguay, Paraguay, Guatemala, and Brazil combine development with relatively high renewable shares, around **57.8%**, **58.8%**, **62.1%**, and **46.5%** respectively.

## Business Recommendations

- Compare countries using carbon intensity rather than emissions alone.
- Incorporate renewable energy share into sustainability benchmarking.
- Include industrial structure when modelling future energy demand.
- Expand future models using urbanisation and energy pricing variables.

## Impact

This project demonstrates how combining economic and environmental indicators can produce richer insights than using GDP or population alone. It also shows the value of feature engineering, database design, and interactive dashboards in evidence-based decision-making.

## Challenges Solved
 
- Inconsistent country naming across datasets.
- Missing values in developing-country records.
- Different reporting years across sources.
- Unit standardization and data harmonization.


## Skills Demonstrated

| **Skill** | **Evidence** |
|----------------|------------------------------------------|
| **SQL** | Advanced analytical queries using `SELECT`, `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`, `CASE`, subqueries, views, aggregate functions, window functions (`RANK`), `NULLIF`, `ROUND`, and data validation techniques|
| **ETL** | Data cleaning, transformation, standardization with Power Query |
| **Database Design** | MySQL relational schema, SQL views, reporting integration |
| **Statistical Analysis** | Linear regression and sustainability indicator analysis |
| **Power BI Development** | Created four DAX measures, dynamic KPI reporting, interactive slicers, filters, and report navigation. |
| **Excel Development** | Built advanced Excel dashboards using PivotTables, PivotCharts, Power Query, INDEX-MATCH, SUMIFS, COUNTIFS, Data Validation, Conditional Formatting, Named Ranges, and interactive controls. |
| **Data Visualization** | 10+ interactive charts and executive dashboards |
| **Business Analysis** | Produced evidence-based insights and recommendations supporting sustainability strategy, environmental performance monitoring, and policy evaluation. |
| **Documentation** | Produced comprehensive technical documentation, including SQL documentation, DAX documentation, architecture diagrams, workflow diagrams, and GitHub project documentation. |
| **Version Control** | Professional GitHub repository with reproducible project structure. |


## Repository Structure

```text
Global-Energy-Consumption-Sustainability-Analysis/
│
├── README.md
├── LICENSE.md
│
├── Data/
│   ├── Data Dictionary.xlsx
│   ├── EIA_Primary_Energy
│   ├── Our_World_in_Data_CO2_Emissions
│   ├── Our_World_In_Data_Renewable_Share_Energy
│   ├── World_Bank_GDP
│   ├── World_Bank_Land
│   ├── World_Bank_Population
│
├── SQL/
│   ├── 01_Create_Database_and_Table.sql
│   ├── 02_Data_Validation.sql
│   ├── 03_Create_Views.sql
│   ├── 04_Business_Analysis_Queries.sql
│   ├── Data_Flow_Diagram.png
│   └── SQL_Technical_Documentation.docx
│
├── Excel_Dashboard/
│   ├── Global Energy Dashboard.xlsx
│   ├── Dashboard.pdf
│   └── Excel_Formula_Documentation.docx
│
├── Power_BI/
│   ├── Global Energy Dashboard.pbix
│   ├── BI_Dashboard.png
│   ├── BI_Dashboard_Page_1.png
│   ├── BI_Dashboard_Page_2.png
│   └── Power_BI_DAX_Measures_Documentation.docx
│
├── Images/
│   ├── BI_Dashboard.png
│   ├── BI_Dashboard_Page_1.png
│   ├── BI_Dashboard_Page_2.png
│   ├── Data_Flow_Diagram.png
│   ├── Excel_Dashboard.png
│
├── Documentation/
│   ├── Original_Academic_Assignment_Brief.pdf
│   └── Project_Architecture_Diagram.pptx
```

## Future Improvements
- Add regression diagnostics and statistical testing.
- Build the workflow in Python for automation and reproducibility.
- Create an automated ETL pipeline.
- Add forecasting for energy demand and emissions.
- Include more sustainability indicators.
- Deploy the solution in a cloud environment.

  **Gianni-Ioannis Poulis**

Data Analyst | Operations Analyst | Sustainability Analyst

- LinkedIn: Gianni-Ioannis Poulis


