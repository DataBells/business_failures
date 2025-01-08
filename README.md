# business_failures
Data Project: Number of business failures in each region of France from 2014 to 2024 by date of Judgment - All economic sectors of activities (Data updated on December - 2024 by Insee)

## About DataSet
The dataset, sourced from insee.fr, has undergone minimal processing. The primary processing involves merging data from multiple files spanning several years and extracting additional information from other sources.

Note: This is the initial iteration, and the work is ongoing. Further analysis and processing will be conducted in subsequent stages.

The data can be imported into Pandas DataFrames for analysis. It currently includes information on business failures from 2014 to 2024, covering all sectors of activity across France, including its regions, departments, and overseas territories.

The National Institute of Statistics and Economic Studies (Institut national de la statistique et des études économiques) has made this data publicly available on their official website in various spreadsheet files. You can access it here: https://www.insee.fr/fr/accueil

## About Data Types

FailureUnit: Number of business units failed in each quarter (Number)
Year: Year (Date(YYYY))
Quarter: One of 4 quarters of the year (String)
Location: Location in France (String)
LocationCategory: Category of locations diveded into 5 types Region(R), Department(D), Country(C), Overseas(O), Other French Overseas Territories(OFOT) (String)
YearQuarterId: Group for quarters (String)
YearGroupId: Group for years (String)
Zone: In which Zone failure units fall (Number)
ZoneCategory: 4 types Low, Medium, High, Very High (String)
Direction: Direction located in France (String)

## Update Soon
