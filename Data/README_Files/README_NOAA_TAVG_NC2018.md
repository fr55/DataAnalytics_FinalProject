# NOAA 2018 Daily Average Temperature Datasets


## Summary
This dataset was prepared for the final project of the course Environmental 
Data Analytics (ENV 872L) at Duke University, Spring 2019.

The dataset contains data from air temperature monitoring North Carolina 
in 2018.

## Database Information

Data were collected using the Search Tool in the National Center for Environmental 
Information of the National Oceanic and Atmospheric Administration (NOAA) Webpage:
https://www.ncdc.noaa.gov/cdo-web.

Data saved in the project folder path ./Data/Raw/ as 
NOAA_TAVG_NC2018_raw.csv on 2019-03-28.

The following selections were made: 
Option				Selection
Discover Data By 		Search Tool
Weather Observation Dataset 	Daily Summaries
Date Range 			2018-01-01 to 2018-12-31
Search For 			States
Search Term 			North Carolina
Output Format 			Custom GHCN-Daily CSV
Station Detail 			Station Name & Geographic Location
Data Type 			Average Temperature. (TAVG)

## Data Content Information
The dataset contains  daily mean air temperature in Fahrenheit in 2018. 

Data from 39 stations in North Carolina (NAD83 lat/long coordinates).

The dataset contains 7 columns. 
Column names without description are self-explanatory.

COLUMN		DESCRIPTION
STATION 	A unique code identifying the site.
NAME 		Station Name
Site ID 	A unique number identifying the site.
LATITUDE 	NAD83
LONGITUDE 	NAD83
DATE 		dd/mm/YY
TAVG 		Daily Average Temperature in °F

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
