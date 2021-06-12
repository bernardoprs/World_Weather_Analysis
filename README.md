# World_Weather_Analysis
World_Weather_Analysis
analysis files: [WeatherPy.ipynb](https://github.com/bernardoprs/World_Weather_Analysis/blob/main/WeatherPy.ipynb) | [VacationPy.ipynb](https://github.com/bernardoprs/World_Weather_Analysis/blob/main/VacationPy.ipynb)

## Purpose
The purpose of the challenge, given that we worked at a Travelpy, a company that creates or proposed your vacation based on the weather preference of the clients, was to create a vacation map that allows use insert their weather preferences to identify potential vacation destinations. For this, we used Google Api's. We also provide the user with recommended ideal hotels with three proffered travel destinations 
##Overview
To create the vacation map, we generated a list of 1,500 random latitudes and longitudes. With the coordinates, we retrieved and compiled a list of the nearest cities using the city module. Then, we used the OpenWeatherMap API to request the current weather data from each unique town on the list. The resulting map provides users with descriptions of the destinations found on our list, including hotel name, city, country, and current weather and description.
To create a vacation map, We made a list of 1,500 random latitudes and longitudes. With the coordinates, we compiled a list of the nearest cities using citipy module, using the OpenWeatherMap  API to extract the weather data from each unique town on the list. The map provides used hotel information based on the weather specification they asked for. 
## Challenge

[Vacation_Seach](https://github.com/bernardoprs/World_Weather_Analysis/tree/main/Vacation_Seach)| [Vacation_Itinerary](https://github.com/bernardoprs/World_Weather_Analysis/tree/main/Vacation_Itinerary)

The challenge consisted of creating an itinerary for someone's vacation, so (they)had to choose their weather preference, and we would show them on a map all of the hotel possibilities. Finally, we had to create two maps, one with the cities in the itineraries and another with the route. 
