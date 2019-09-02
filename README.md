# WeatherPy

## Project Overview
The goal of this project was to find a random sampling of over 500 cities from all over the world, retrieve current weather data for the cities (temperature, humidity, cloud coverage and wind speed), and analyze the data compared to the city latitude.

## Analysis Performed
For cities found, the following scatterplots were created:
  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude
  * Wind Speed (mph) vs. Latitude

## Output
A csv file for city and weather data found will be exported along with images of the 4 scatterplots.  The data can be found in the project folder named 'output_data'.

## Summary of Observations
  * As is expected, temperatures rise the closer a city is to the equator (0 degree latitude). 
  * Humidity does not have a strong relationship to latitude however there are a higher concentration of cities in the northern hemisphere(above 0 degrees latitude) with humidity hovering above 80%.
  * Cloud coverage also does not have a strong relationship with latitude. 
  * Wind Speeds tend to be between 0-10 MPH regardless of latitude.
  
## Project Dependencies
This project uses the following libraries:
  * matplotlib.pylot
  * pandas
  * numpy
  * requests
  * time
  * datetime
  

## Project Environment
This is a jupyter notebook project. Open the WeatherPy.ipynb file in jupyter nobooks, restart Kernal and run all to view data results and charts illustrating analysis.
