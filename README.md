
# Carbon Emission Data Analysis Project

## Overview

The Carbon Emission Data Analysis Project is aimed at exploring and analyzing carbon emission data. The project leverages SQL for data manipulation and Power BI for visualization to gain insights into carbon emissions and their trends.

## Features

- **SQL Data Exploration**: The project begins with SQL queries to understand the dataset. It checks for null values in different columns, examines the range of years, and identifies distinct series within the dataset.

- **Data Splitting**: The dataset is split into two tables, 'emissions' and 'perCapital,' for different series, making it easier to work with them separately.

- **Data Analysis**: The SQL queries include various analyses such as finding countries with the highest and lowest emissions per capita, identifying significant changes in emissions over time, and determining the top five countries with the highest carbon emissions.

- **Power BI Visualization**: The project integrates Power BI for data visualization, allowing you to create informative charts, graphs, and dashboards to communicate the findings effectively.

## Data Analysis Description

## 2. About the Dataset

### a. Carbon Emission Database
- **Source**: [Kaggle](https://www.kaggle.com/datasets/vineethakkinapalli/united-nations-environment-data?select=Water+and+Sanitation+Services.csv)
- **Overview**: This database contains information about carbon emissions, both per capita in countries and total emissions worldwide.
- **Tools Used**: SQL for data cleaning and analysis, Power Bi for visualization.

### b. Reduced Carbon Emission Database
- **Source**: [UN - Environment Program](https://www.unep.org/interactive/six-sector-solution-climate-change/)
- **Overview**: This database provides insights into how carbon emissions can be reduced across six different sectors.

### Data Splitting
The 'emissions' and 'perCapital' tables are created to separate data for 'Emissions (thousand metric tons of carbon dioxide)' and 'Emissions per capita (metric tons of carbon dioxide)' series. This simplifies the analysis for these distinct categories.

### Emissions per Capita Analysis
- The analysis focuses on the 'Emissions per capita' series for the United States of America.
- It finds the minimum and maximum values, identifying that the lowest emissions occurred in 2017, and the highest in 1975.
- Further analysis calculates the change in emissions per capita between 1975 and 2017.

### Emissions Analysis
- The 'emissions' table is explored, and data for the United States of America is extracted.
- The analysis finds the minimum and maximum emissions for the USA.
- It identifies that the lowest emission value is in 1975, and the highest in 2005.
- Finally, the top five countries with the highest carbon emissions are determined.

## Visualizations

Power BI is used to create visual representations of the data, including charts and graphs, to provide a clear and concise presentation of the analysis. Some potential visualizations based on the SQL queries may include:

- A line chart to show the change in emissions per capita in the United States from 1975 to 2017.
- A bar chart to display the top five countries with the highest carbon emissions.
- A table or matrix visual to present key statistics, such as the minimum and maximum values for emissions and emissions per capita.

These visualizations help in understanding the data and conveying the findings effectively to stakeholders and decision-makers.
