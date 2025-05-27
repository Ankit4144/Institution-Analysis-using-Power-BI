# Institution Analysis using Power BI

## Project Overview

This Power BI project analyzes global education institutions and their associated public expenditures. The analysis combines insights from two datasets: one detailing institutional performance metrics and another outlining public spending across countries. This project was structured around 10 key tasks involving data transformation, DAX calculations, filtering, and visualization.


## Datasets Used
-  [Download Dataset](https://drive.google.com/file/d/1iX5Sw1h4GDgOKQEcj8Zqw0SH0UvZUU36/view)


### 1. **Expenditure Dataset**
Provides information on direct public expenditures by country over different years.

**Key Columns**:
- `country`
- `institute_type`
- `direct_expenditure_type`
- Expenditure data for years: `1995`, `2000`, `2005`, `2009`, `2010`, `2011`


### 2. **Data Dataset**
Contains global ranking details and performance metrics of educational institutions.

**Key Columns**:
- `world_rank`, `institution`, `country`, `national_rank`
- `quality_of_education`, `alumni_employment`, `quality_of_faculty`
- `publications`, `influence`, `citations`, `broad_impact`, `patents`
- `score`, `year`


## Key Tasks Completed

1. **Calculated** the average public expenditure for 2005 across all countries.
2. **Summed** total publications for institutions based in the UK.
3. **Filtered** the dataset to only show institutions with a world rank below 100.
4. **Calculated** the total expenditure across all available years for each country.
5. **Created a DAX formula** to ignore filters on the year column and compute total score.
6. **Measured** the growth in expenditure for Austria from 1995 to 2000.
7. **Formatted** all expenditure values to include a currency symbol with zero decimals.
8. **Calculated** the total expenditure per country across all years.
9. **Built multiple report sheets** with the following visuals:
   - (a) Patents by country and quality of faculty
   - (b) Total publications and citations in the USA using Power BI Q&A
   - (c) Key metrics for the top 5 institutions by world rank
   - (d) Distribution of direct_expenditure_type for 2011 with OECD Average highlighted
10. **Created a workspace** named `"Institution Analysis"` and set up a **daily dataset refresh** at 6 AM.


## Tools & Features Used

- Power BI Desktop
- Power BI Q&A visual
- DAX formulas
- Data Modeling
- Data Formatting
- Scheduled Data Refresh
- Multi-Sheet Report Design

## Outcome

- Analyzed trends in public expenditure and their link to institutional performance
- Created actionable insights using data filters, rankings, and expenditure trends
- Delivered a clean, structured multi-visual report for stakeholders





