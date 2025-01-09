# business_failures
Data Project: Number of business failures in each region of France from 2014 to 2024 by date of Judgment - All economic sectors of activities (Data updated on December - 2024 by Insee)

### About DataSet
The dataset, sourced from insee.fr, has undergone minimal processing. The primary processing involves merging data from multiple files spanning several years and extracting additional information from other sources.

Note: This is the initial iteration, and the work is ongoing. Further analysis and processing will be conducted in subsequent stages.

The data can be imported into Pandas DataFrames for analysis. It currently includes information on business failures from 2014 to 2024, covering all sectors of activity across France, including its regions, departments, and overseas territories.

The National Institute of Statistics and Economic Studies (Institut national de la statistique et des études économiques) has made this data publicly available on their official website in various spreadsheet files. You can access it here: https://www.insee.fr/fr/accueil
### About Data Types
| ColumnName    | DataType |
| -------- | ------- |
| FailureUnit  | Number   |
| Year | Date(YYYY)     |
| Quarter   | String   |
| Location  | String  |
| LocationCategory | String     |
| YearQuarteId   | String  |
| YearGroupId | String   |
| Zone | Number     |
| ZoneCategory   | String   |
| Direction  | String  |

<br>

### Column Name Description
FailureUnit: Number of business units failed in each quarter <br>
Year: Year <br>
Quarter: One of 4 quarters of the year <br>
Location: Location in France <br>
LocationCategory: Category of locations diveded into 5 types Region(R), Department(D), Country(C), Overseas(O), Other French Overseas Territories(OFOT) <br>
YearQuarterId: Group for quarters <br>
YearGroupId: Group for years <br>
Zone: In which Zone failure units fall <br>
ZoneCategory: 4 types Low, Medium, High, Very High <br>
Direction: Direction located in France <br>
### Update Soon
