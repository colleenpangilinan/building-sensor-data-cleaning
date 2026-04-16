# Building Energy Sensor Data Transformation & Cleaning

End-to-end SQL data cleaning and transformation pipeline 
built on a real-world IoT dataset of building sensor 
readings from UC Berkeley facilities.

Dataset source: Luo et al. (2022), "A three-year dataset 
supporting research on building energy management and 
occupancy analytics." Scientific Data.
https://doi.org/10.1038/s41597-022-01257-x

## What I Did
- Built SQL workflows to clean, standardize, and transform 
  one month of timestamped sensor readings
- Applied outlier detection, winsorization, and 
  missing-value interpolation for time-series data
- Resolved entity mismatches across 5,276 metadata records
- Identified 771 time-gap readings requiring interpolation

## Tools
PostgreSQL, Python, pandas, SQL (CTEs, window functions)

## Key Concepts
Data cleaning, entity resolution, outlier detection, 
winsorization, time-series interpolation, EDA
