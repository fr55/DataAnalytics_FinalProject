# EPA Air Quality Datasets


## Summary
This dataset was prepared for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2019

The dataset contains data from air quality monitoring of PM2.5 and PM10 in North Carolina in 2018.

## Database Information
Data were collected using the Download Daily Data tool (https://www.epa.gov/outdoor-air-quality-data/download-daily-data).
The following selections were made: 
* PM2.5 and PM10 (Pollutant)
* 2018 (Year)
* North Carolina (Geographic Area)
* Download CSV (spreadsheet)


csv files were saved as `EPAair_PM25_NC2017_raw.csv`, and `EPAair_PM10_NC2018_raw.csv`. 

PM25 Data were accessed 2018-12-10 and PM25 Data were accessed 2018-03-28

## Data Content Information
Information gathered from: https://www.epa.gov/outdoor-air-quality-data/air-data-basic-information and https://aqs.epa.gov/aqsweb/documents/AQS_Format.html

Column names without descriptors are self-explanatory.

Date: month/day/year
Source: AQS (Air Quality System) or AirNow
Site ID: A unique number within the county identifying the site.
POC: “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site.
Daily Mean PM2.5 or PM10 Concentration: numeric value
Units: units for concentration

Daily_AQI_VALUE: Air quality index (range 0-500). Levels: 
0-50: Good (green)
51-100: Moderate (yellow)
101-150: Unhealthy for sensitive groups (orange)
151-200: Unhealthy (red)
201-300: Very unhealthy (purple)
301-500: Hazardous (maroon)

Site Name
DAILY_OBS_COUNT: number of observations per day
PERCENT_COMPLETE
AQS_PARAMETER_CODE
AQS_PARAMETER_DESC
CBSA_CODE
CBSA_NAME
STATE_CODE
STATE
COUNTY_CODE
COUNTY
SITE_LATITUDE
SITE_LONGITUDE

## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Kateri Salk** (kateri.salk@duke.edu)