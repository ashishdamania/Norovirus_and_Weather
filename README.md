This is the repository for exploring 
the relationship between norovirus outbreaks and weather parameters - Temperature and Precipitation in 18 U.S. States from 2000-2018. The norovirus outbreak data is limited to person-to-person transmission related outbreaks.

R source code is contained within Merged_data.rmd file. 

Following R packages needs to installed prior to running the code:
- tidyverse (for data transformation)
- vroom (for reading multiple csv files)
- MASS (for data description)
- broom (for converting regression output to tables)
- glmmTMB (for Negative binomial regression)
- geofacet (for creating map layout)
- sf (dependency pacakage for geofacet)
- gt (for generating table)
- scales (scaling values)
- janitor (for cleaning column names)

The raw data sources include:
- National Outbreak Reporting System
- National Oceanic And Atmospheric Administration
- Population data CDC wonder database 

 
