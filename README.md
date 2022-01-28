# Web Scraping

## Problem Statement

### To scrape weather data from a website and store it in a dataframe.

## URL used for Web Scraping

- http://www.estesparkweather.net/archive_reports.php?date={ 'date to be scraped' }

## Data Dictionary


|Feature|Type|Description|
|---|---|---|
|Average temperature (°F)|float64|Average temperature in a day|
|Average humidity (%)|int64|Average humidity in a day|
|Average dewpoint (°F)|float64|Average dewpoint in a day|
|Average barometer (in)|float64|Average barometer reading in a day|
|Average windspeed (mph)|float64|Average windspeed in a day|
|Average gustspeed (mph)|float64|Average gustspeed in a day|
|Average direction (°deg)|int64|Average direction of wind in a day|
|Rainfall for month (in)|float64|Rainfall for month|
|Rainfall for year (in)|float64|Rainfall for year|
|Maximum rain per minute|float64|Maximum rain per minute in a day|
|Maximum temperature (°F)|float64|Maximum temperature in a day|
|Minimum temperature (°F)|float64|Minimum temperature in a day|
|Maximum humidity (%)|int64|Maximum humidity in a day|
|Minimum humidity (%)|int64|Minimum humidity in a day|
|Maximum pressure|float64|Maximum pressure in the day|
|Minimum pressure|float64|Minimum pressure in a day|
|Maximum windspeed (mph)|float64|Maximum windspeed in a day|
|Maximum gust speed (mph)|float64|Maximum gust speed in a day|
|Maximum heat index (°F)|float64|Maximum heat index in a day| 


## Summary
The work starts with scraping of data from the above-mentioned URLs, after getting the response from an API required fields are mapped and stored into a dataframe. The data collected for the specified interval of time.

The data is cleaned, which includes removal of special characters and renaming of columns with appropriate names.

Then the final dataframe is exported as a pickle file

