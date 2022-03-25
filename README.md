# World_Weather_Analysis

### Project Overview
The purpose of this project is to explore the relationship between city location and experienced weather using python and various packages. This will allow us to create a searchable database of locations that have ideal weather for vacations. Furthermore we allow users to look at hotels in their desired area and plot out routes between destinations.

### Data

Both an OpenWeather API key and Gmaps API key will be needed in a config.py file. Other software includes Python, citipy, Pandas, Matplotlib, SciPy, and Jupyter Notebook.

With the OpenWeather API the user will create a database of 600+ cities. The Gmaps key is required for plotting on a Google Maps view.

### Results

##### Vacation Search

Vacation Search takes the information gained in the weather database from OpenWeather and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have an daily maximum temperature between 75 and 88 degrees farinheit.

![](https://github.com/roeggealissa/World_Weather_Analysis/blob/6dc91cb26a5f58bcf5c3c81d1a389e213589653b/Vacation_Search/WeatherPy_Vacation_Map.png)

##### Vacation Itinerary

Vacation Itinerary allows a user to plot routes between destinations they may want to visit. In addition the user can view information on a recommended hotel in the area. The images below demonstrate a plotted route and hotel information for a trip through Lybia and Tunisia. The two pieces of information can be displayed at once but for clarity this demonstration has them in two difference instances.

![](https://github.com/roeggealissa/World_Weather_Analysis/blob/6dc91cb26a5f58bcf5c3c81d1a389e213589653b/Vacation_itinerary/WeatherPy_travel_map.png)
![](https://github.com/roeggealissa/World_Weather_Analysis/blob/6dc91cb26a5f58bcf5c3c81d1a389e213589653b/Vacation_itinerary/WeatherPy_travel_map_markers.png)
