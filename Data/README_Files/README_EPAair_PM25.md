# EPA Air Quality PM 2.5 Dataset


## Summary
This dataset was prepared for the final project of the course Environmental 
Data Analytics (ENV 872L) at Duke University, Spring 2019.

This dataset contains data from air quality monitoring of PM2.5 in North Carolina 
in 2018.

## Database Information

Data were obtained using the Download Daily Data Tool in the United States 
Environmental Protection Agency (EPA) webpage: 
https://www.epa.gov/outdoor-air-quality-data/download-daily-data

Data saved in the project folder path ./Data/Raw/ as 
EPAair_PM25_NC2018_raw.csv on 2019-03-31.

The following selections were made:
Option			Selection	
Pollutant		PM2.5
Year			2018
Geographic Area		North Carolina
Monitor Site		All Sites
Download		Download CSV (spreadsheet)

## Data Content Information
The dataset contains daily mean PM2.5 concentration in ug/m3 in 2018. 

Data from 24 stations in 21 different counties of North Carolina (NAD83 lat/long coordinates)

The dataset contains 19 columns. 
Column names without description are self-explanatory.

COLUMN				DESCRIPTION
Date				mm/dd/YY
Source				AQS (Air Quality System)
Site ID				A unique number identifying the site
POC				“Parameter Occurrence Code”, distinguishes differ-
				ent instruments that measure the same parameter
				at the same site
Daily Mean PM2.5 Concentration
Units				Concentration Units
DAILY_OBS_COUNT			AQI = Air quality index	
PERCENT_COMPLETE
AQS_PARAMETER_CODE
AQS_PARAMETER_DESC
CBSA_CODE
CBSA_NAME
STATE_CODE			A unique number identifying the State.
STATE
COUNTY_CODE			A unique number identifying the County.
COUNTY
SITE_LATITUDE			NAD83
SITE_LONGITUDE			NAD83

## Naming conventions and file formats
Files are named according to the Environmental Data Analytics (ENV 872L) 
naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Felipe Raby Amadori** (felipe.raby.amadori@duke.edu)