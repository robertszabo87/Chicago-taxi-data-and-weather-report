# Chicago-taxi-data-and-weather-report
This project is a comprehensive data pipeline designed for extracting, transforming, and analyzing various datasets related to Chicago taxi-and weather data, including JSON data scraping, web scraping, taxi trip data retrieval, weather data processing, and data transformation for mapping and visualization. 

This repository contains several scripts for data extraction, transformation, and analysis related to the city of Chicago. The scripts cover various tasks including JSON scraping, web scraping, fetching and processing taxi and weather data, creating date dimensions, and integrating data for mapping and visualization.

Json Scraping:
This script reads and parses a JSON file containing Spotify playlist data.

Web Scraping:
This script scrapes data from the Wikipedia page on community areas in Chicago.

Get Taxi Data:
This script fetches taxi trip data from the City of Chicago data portal and processes it.

Get Weather Data:
This script retrieves historical weather data using the Open Meteo API and processes it into a pandas DataFrame.

Date Dimension:
This script creates a date dimension DataFrame spanning from January 1, 2023, to January 1, 2028, with additional date-related fields.

Chicago Data to Mapping:
This script processes Chicago taxi trips and weather data for mapping and visualization.

Transform Load:
This script transforms and loads the taxi trip and weather data, updating master tables for payment types and companies.

Local Visualisations:
This script generates visualizations for the processed data using Plotly.

Script 09 and 10 uses the same functions, but in AWS environment!
