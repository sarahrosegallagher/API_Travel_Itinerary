# API Travel Itinerary

## Weather Database
Weather Database.ipynb and csv file

Tasks

* generate 2,000 randomized coordinates with latitude and longitude

* use citipy to find the nearest city to each coordinate, creating a list

* use OpenWeatherMap API to extract and load weather data for each city

* format and write the city weather database to a csv file for use in following tasks

## Customer Travel Destinations Map
Vacation_Search.ipynb, WeatherPy_vacation.csv, Weatherpy_vacation.png

Tasks

* import the city weather database and refine based on user input of preferred max temperatures

* use Google Places API to extract and load nearby hotel information for each city in the preferred dataframe 

* create a map with a heatmap layer, a marker layer, and infoboxes for each city with the relevant data points (weather, hotel, location)

## Travel Itinerary Map 
Vacation_Itinerary.ipynb and png files 

Tasks

* create a travel itinerary dataframe and map for four cities from the preferred dataframe

* use a directions layer on the gmap figure to display the travel route 