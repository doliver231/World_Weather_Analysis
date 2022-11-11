# World_Weather_Analysis

## Overview

To really get a glimpse of the different cultures, landscapes, and diversity, one must take the opportunity to travel the world. Factors such as weather conditions can highly influence the overall travel experience. The purpose of this project is to collect, analyze and visualize weather data across cities worldwide and to provide travelers with a tool that will allow them to determine their travel destination based on weather conditions.

## Resources

CSV Files: Weather_Database.csv, WeatherPy_vacation.csv

Jupyter Notebook Files: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

Python: Python v3.7.6, Dependencies: Pandas, Gmaps, CitiPy, Python Requests for APIs, NumPy, Python Random

## Analysis

### Weather Database

A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.

The following data was retrieved from the API call:

** Latitude and longitude
** Maximum temperature
** Percent humidity
** Percent cloudiness
** Wind speed
** Current Weather description

##### Using code: city_data_df.head(10) to retrieve our DataFrame
![First 10 items of City & Weather DataFrame]()

### Vacation Search

Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers on a marker layer-map.

##### An interactive map with markers was created based on the specific minimum and maximum temperatures input by the user:
![User Input]()
![GMap with Markers after user input temperatures](https://github.com/doliver231/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary

Using the Google Directions API, a sample itinerary was created that shows the route between four cities in Colorado, Wyoming, and Nebraska (United States).

![Rountrip directions route between 4 cities](https://github.com/doliver231/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

##### Each city marker reveals descriptive info inlcuding hotel name & temperature
![Itinerary city markers](https://github.com/doliver231/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
