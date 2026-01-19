# Beijing Air Quality Dashboard (Power BI)

An interactive Power BI dashboard that analyzes air quality trends using hourly sensor data. The report focuses on pollutant levels and environmental conditions to highlight patterns across time and support quick, high-level monitoring.

## What this project shows
- Hourly and monthly trends for key pollutants (CO, NO2, NOx, NMHC, Benzene)
- KPI style cards to track current or average levels
- Visual comparisons across pollutants and time periods
- Weather context using temperature (T), relative humidity (RH), and absolute humidity (AH)

## Files in this repo
- Beijing-AirQuality.pbix - Power BI report file
- AirQualityUCI.xlsx - source dataset used by the report

## Dataset overview
- Granularity: hourly readings
- Rows: 9,357
- Time period: 2004 to 2005
- Main fields: Date, Time, CO(GT), NMHC(GT), NOx(GT), NO2(GT), sensor signals (PT08.*), T, RH, AH

## How to view
1. Install Power BI Desktop.
2. Open Beijing-AirQuality.pbix.
3. If prompted, update the file path to AirQualityUCI.xlsx and refresh.

## Tools used
Power BI (Power Query for cleaning and shaping, DAX for measures), Excel dataset
