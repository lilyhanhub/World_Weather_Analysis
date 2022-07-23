# World_Weather_Analysis
## Overview of the Analysis

PlanMyTrip app,  



## Results
### Weather Database
I generated a set of 2,000 random latitudes and longitudes, retrieved the nearest cities from citipy module, and then performed an API call with the OpenWeatherMap to retrieve the following weather information for each of the 692 cities: latitude and longitude, maximum temperature, percent humidity, percent cloudiness, wind speed, and weather description. Lastly, I added the data to a new DataFrame and exported it as a [.csv file](Weather_Database/WeatherPy_Database.csv). 

### Vacation Search
I used input statements to retrieve customer weather preferences(75-85°F), identified 212 potential travel destinations and nearby hotels, and created a marker layer map with pop-up markers for those destinations. 
![WeatherPy_vacation_map](Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary 
I used the Google Directions API and created a travel itinerary showing the route between four cities in Brazil chosen from the customer's possible travel destinations. 
![WeatherPy_travel_map](Vacation_Itinerary/WeatherPy_travel_map.png)
Lastly, I created a marker layer map with a pop-up marker for each city on the itinerary. 
![WeatherPy_travel_map_markers](Vacation_Itinerary/WeatherPy_travel_map_markers.png)




## Resources
* APIs 
  * OpenWeatherMap
  * Google Maps
  * Google Places
  * Google Directions
* Software: Python 3.9.12 | Jupyter Notebook 6.4.8
 
