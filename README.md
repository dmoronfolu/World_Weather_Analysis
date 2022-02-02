# World_Weather_Analysis

Overview

The purpose of this project to create travel itineraries from four different cities from a list of potential travel destinations that we generated. In the first part of the project, we generated a set of 2000 random latitudes and longitudes, retrieved the nearest city and performed an API call with the OpenWeatherMap

In the second deliverable, we generated a list of hotels and we dropped any rows in the hotel dataframe where the hotel name is not found. In the third and final deliverable, we selected four cities in the same country and close to each other on the map and gathered travelling directions between the four cities. This last one was a little challenging because there were several cities on my map that were appear close to each other but was unable to generate any routes to each other. I discovered that while some of these cities were close to each other, several were in different countries, which explained why I was unable to generate a valid output. I had to zoom to get cities close enough to each other to generate travelling directions. 

Results:

<img width="1048" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/85265504/152089769-b7015429-2215-43c1-9ad4-c32449037b3b.png">

<img width="1071" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/85265504/152089881-59ff57ce-b1ee-4c2f-97c5-f9529f40ea29.png">

<img width="1029" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/85265504/152089800-fffdcf9b-6e5a-49d3-9974-1f690b52b800.png">
