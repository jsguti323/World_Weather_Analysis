# World_Weather_Analysis
## Overview
How many times have you planned a trip only to discover the day of departure that your destination is experiencing bad weather? Often times when planning a vacation, the consumer fixates on the destination but does not always consider weather conditions. To save yourself time and a headache planning your next trip, instead of searching every one of your preferred destinations and comparing their respective weather conditions, why not instead search for cities based on your preferred weather conditons and then choose a destination from that much smaller list? That's exactly the service PlanMyTrip provides to their customers. With PlanMyTrip, customers are able to filter a database of cities from all over the world based on their preferred weather conditions and find hotels in cities that match their search criteria.  

## Results

### Weather DataBase
![city_database](https://user-images.githubusercontent.com/99751636/177393177-23cfc77b-d135-485f-aba1-4f1ee19299f6.png)

* We began by generating 2000 random coordiantes and found the cities closest to those coordinates. 
* Once we compiled a list of those cities, we were able to perform an API call to OpenWeatherMap in order to pull relevant information we needed for each city, i.e. the name of the city, it's maximum temperature, a short description of the weather, etc. Finally, we created a new DataFrame feating our updated weather data.

### Vacation Search
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/99751636/177393225-0c1a8634-eb4f-4065-a3ba-b3afbc37234d.png)

* We were able to create input boxes that would allow our guests to let us know their ideal temperature range when on vacation. 
* Using that information, we were able to find all the cities whose maximum temperatures fell within that range. 
* We then created a map featuring only those cities, complete with pop-up markers that displayed each city's information.

### Vacation Itinerary
![WeatherPy_travel_map](https://user-images.githubusercontent.com/99751636/177393412-eb36f442-d27d-44a4-bbf1-beb1494dd202.png)
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/99751636/177393420-29e5846c-0271-4ebc-ae5c-1f44c90662b9.png)

* From our new map, we chose four cities near each other and create a map featuring directions between those four cities.
* For each city, we also included the name of the recommended hotel in that city, as well as a description of the city's weather conditions.
