# World_Weather_Analysis
APIs to Visualize Weather Data

## Overview of the analysis:
The purpose of World_Weather_Analysis, retrieving and analyzing weather data using google maps API and OpenWeather API. 

 During the analysis following were learned and applied in the rideshare data visualization:
  * Retrieve and use data from an API "get" request to a server.
  * Retrieve and store values from a JSON array.
  * Use try and except blocks to resolve errors.
  * Create scatter plots using the Matplotlib library, and apply styles and features to a plot.
  * Perform linear regression, and add regression lines to scatter plots.
  * Create heatmaps, and add markers using the Google Maps API.

## Tasks Accomplished:
  * Collect the Data
  * Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
  * Use the citipy module to list the nearest city to the latitudes and longitudes.
  * Use the OpenWeatherMap API to request the current weather data from each unique city.
  * Parse the JSON data from the API request.
  * Exploratory Analysis with Visualization
  * Create scatter plots and linear regression of the weather data and determine the correlations.
  * Create a series of heatmaps using the Google Maps and Places API.
  * Visualize Travel Data
  * Create a heatmap with pop-up markers that can display information on specific cities based on a customer’s travel preferences.

## Results:

1. Retrieve Weather Data
  * Jupyter Notebook: Weather_Database.ipynb
  * Result csv file: WeatherPy_challenge.csv
    ![image](https://user-images.githubusercontent.com/79486450/114320685-124a9c80-9ae5-11eb-818c-162e65a05b36.png)

2. Create a Customer Travel Destinations Map
  * Jupyter Notebook: Vacation_Search.ipynb
  * Result csv file: WeatherPy_vacation.csv
  * Result dataframe screenshot: Hotel_DataFrame.png
  * Google marker_layer map
    ![WeatherPy_vacation_map png](https://user-images.githubusercontent.com/79486450/114320709-33ab8880-9ae5-11eb-9aaf-99aed8acd030.png)

3. Create a Travel Itinerary Map
  * Jupyter Notebook: Vacation_Itinerary.ipynb
  * The route between four cities from the customer’s possible travel destinations:
  * ![WeatherPy_travel_map](https://user-images.githubusercontent.com/79486450/114320728-56d63800-9ae5-11eb-96e1-27413f9298af.png)

  * Map with pop-up markers for the four cities:
    ![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/79486450/114320734-5d64af80-9ae5-11eb-942a-664f8af69cb1.png)


