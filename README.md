# World_Weather_Analysis
# Overview.
  
  Weather conditions affect travel behavior for tourists and influence their travel experience. The purpose of this analysis is to collect and analyze weather conditions across different cities worldwide. The analysis also helps the tourists determine their destination based on the weather conditions.

# Resources Used to Complete Analysis.

1) Different CSV files;

2) Jupyter Notebook files;

3) Dependencies: Pandas, Numpy, Matplotlib, Datetime, Time, SciPy API keys, CitiPy, Requests, JSON.

# Process.

# Retrieve the Weather Data:

A random set of 2,000 latitudes and longitudes was generated, an API call was made using the OpenWeatherMap for the some nearby cities. 
The following data was retrieved from the API call:
* Latitude and Longitude
* Humidity
* Cloudiness
* Wind Speed
* Maximum Temperature
* Current weather description

The Data Frame was created to get the initial list of potential cities:

![Dataframe weather summary](https://user-images.githubusercontent.com/104453593/173970216-a5f96144-d2c9-4a50-b5cd-a0e478f983a2.PNG)


# Create a Customer Travel Destinations Map
Based on different traveler's weather preferences, the data frame was cleaned for null hotel entries. 
A marker layer map was created that has pop-up markers for each city on the map.
 
 ![WeatherPy_vacation_map](https://user-images.githubusercontent.com/104453593/173971736-764c7336-61d4-46e6-b43b-84c1d6319b4a.PNG)
 
 
# Create a Travel Itinerary Map
The list was narrowed down to 4 cities in the same country and a map was created.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/104453593/173974162-34fd0428-b7c1-42ff-b878-63ca89bf244b.PNG)


Markers were added to the map of four cities.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/104453593/173974799-5a5f01c5-ddd4-40e2-b94a-d13e0440d89e.PNG)

