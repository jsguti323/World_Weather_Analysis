# World_Weather_Analysis
## Overview
We collected and anaylzed data across cities worldwide so PlanMyTrip could recommend hotels to clients based on weather preferences. We did so by creating a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process entailed collecting, analyzing, and visualizing the data.
## Results
### Weather DataBase
We began by generating 2000 random coordiantes and found the cities closest to those coordinates. Once we compiled a list of those cities, we were able to perform an API call to OpenWeatherMap in order to pull relevant information we needed for each city, i.e. the name of the city, it's maximum temperature, a short description of the weather, etc. Finally, we created a new DataFrame feating our updated weather data.
### Vacation Search
This is where our guest recommendations came into effect. We were able to create input boxes that would allow our guests to let us know their ideal temperature range when on vacation. Using that information, we were able to find all the cities whose maximum temperatures fell within that range. When then created a map featuring only those cities, complete with pop-up markers that displayed each city's information.
### Vacation Itinerary
From our new map, we chose four cities near each other and we created a map featuring directions between those four cities.
## Summary
This project gave me what has probably been my first real test of being a data analyst, as it was the first time I had really hit a wall and got through the challenge with a whole lot of felp from google. The most challenging part was probably deliverable 3. It took me so long to figure out how to pull tuples from a DataFrame usng to_numpy. But with a lot of trial, error, and overstackflow I eventually got it down. 
