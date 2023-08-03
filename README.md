# Data preparation for Tableau using Python

Clean and transform data and write file to .csv, .xlsx or GeoJSON to be used as a data source for Tableau dashboards and visualizations.

## OECD - Convert ISO3 codes to country names
Get country names from ISO-3 codes for datasets from [OECD Data]('https://data.oecd.org/') using country converter.
Notebook

### Unemployment rates in the EU
- explore data frame containing information on unemployment rates in the EU from 2002 to 2022
- get couintry names, rename columns, convert to datetime
- libraries used: pandas, numpy, country_converter
- Viz: [Unemployment rates in the EU]('https://public.tableau.com/app/profile/anna8476/viz/Unemployment_Rates_EU/Dashboard1')
### Inflation rates in OECD countries
- explore dataset about quarterly inflation rates in OECD countries between 20128-2023
- get country names, select subset of columns, convert to datetime, replace values where country is OECD
- libraries used: pandas, numpy, country_converter
- Viz: [Inflation in OECD countries]('https://public.tableau.com/app/profile/anna8476/viz/InflationOECD/Dashboard2')

## Water fountains in Zürich
- Notebook
- explore two datasets containing information on water fountains in Zürich
- select and extract columns of interest and create new data frame
- libraries used: pandas, geopandas, matplotlib
- Viz: [Public water fountains in Zürich]('https://public.tableau.com/app/profile/anna8476/viz/WaterfountainsZrich/Dashboard1')
