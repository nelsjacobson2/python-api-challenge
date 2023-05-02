# python-api-challenge

WeatherPy and VacationPy
In this project, we are analyzing the weather patterns of cities worldwide. We are utilizing the OpenWeatherMap API to retrieve weather data for each city.

We have broken the project into two parts:

WeatherPy: In this part, we use Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. This script generates a series of scatter plots to showcase the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
VacationPy: In this part, we use Jupyter Notebook, Pandas, Matplotlib, and the Google Maps API to create a heat map and markers that indicate ideal hotels based on a given set of weather criteria.
WeatherPy
In the WeatherPy notebook, we use the OpenWeatherMap API to get weather information for random cities across the globe, and analyze the resulting data. We then use Matplotlib and Pandas to create scatter plots that show the relationship between various weather metrics and a city's latitude.

Prerequisites
Python 3
Jupyter Notebook
OpenWeatherMap API key
Getting Started
Clone this repository to your local machine.
In the weatherpy.ipynb file, enter your OpenWeatherMap API key in the api_keys variable.
Run the notebook to generate the scatter plots.
VacationPy
In the VacationPy notebook, we use the Google Maps API and a csv file of cities and their weather information to create a heat map that shows the humidity of each city in our dataset. We then narrow down the list of cities to those that meet certain criteria, such as having a temperature between 70 and 80 degrees, zero cloudiness, and wind speeds less than 10 mph. We then use the Geoapify API to find hotels within a 10,000 meter radius of each of these cities, and plot these hotels as markers on the heatmap.

Prerequisites
Python 3
Jupyter Notebook
Google Maps API key
Geoapify API key
Pandas
Matplotlib
hvPlot
Getting Started
Clone this repository to your local machine.
In the vacationpy.ipynb file, enter your Google Maps API key in the gmaps.configure(api_key=) function.
In the api_keys.py file, enter your Geoapify API key in the geoapify_key variable.
Run the notebook to generate the heat map and markers.

Contributors
This project was created by Nels Jacobson.
