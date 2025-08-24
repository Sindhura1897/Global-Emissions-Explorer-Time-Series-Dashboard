# Which countries have a carbon tax? - Data package

This data package contains the data that powers the chart ["Which countries have a carbon tax?"](https://ourworldindata.org/grapher/carbon-tax-instruments?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on November 29, 2024.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Covered by tax instrument in at least one sector
This data indicates whether at least one sector(-fuel) is covered by at least one carbon tax at the national level, or only at the sub-national level, or whether no sector is covered.
Last updated: October 19, 2023  
Next update: December 2024  
Date range: 1989–2022  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Dolphin and Xiahou (2022) – with major processing by Our World in Data

#### Full citation
Dolphin and Xiahou (2022) – with major processing by Our World in Data. “Covered by tax instrument in at least one sector” [dataset]. Resources for the Future, “World Carbon Pricing Database” [original data].
Source: Dolphin and Xiahou (2022) – with major processing by Our World In Data

### What you should know about this data
* This data primarily focuses on economic instruments targeting carbon dioxide (CO₂) emissions.
* In some cases these instruments also cover other greenhouse gases. However, any pricing mechanisms that specifically target non-CO₂ gases (such as methane or nitrous oxide) are not included.
* A country is considered to have a carbon tax or emissions trading system if at least one IPCC sector or gas is covered by the instrument. These instruments do not need to cover all sectors within the economy for this to apply.

### Source

#### Resources for the Future – World Carbon Pricing Database
Retrieved on: 2023-10-19  
Retrieved from: https://github.com/g-dolphin/WorldCarbonPricingDatabase/  


    