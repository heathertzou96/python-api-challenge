# WeatherPy Project

### Task
* Create a Python script to visualize the weather of 500+ randomly selected cities across the world of varying distance from the equator using a simple Python library, the OpenWeatherMap API.
* Build a series of scatter plots to showcase the following relationships:
  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude
  * Wind Speed (mph) vs. Latitude
* Run a linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
  * Northern Hemisphere - Temperature (F) vs. Latitude
  * Southern Hemisphere - Temperature (F) vs. Latitude
  * Northern Hemisphere - Humidity (%) vs. Latitude
  * Southern Hemisphere - Humidity (%) vs. Latitude
  * Northern Hemisphere - Cloudiness (%) vs. Latitude
  * Southern Hemisphere - Cloudiness (%) vs. Latitude
  * Northern Hemisphere - Wind Speed (mph) vs. Latitude
  * Southern Hemisphere - Wind Speed (mph) vs. Latitude
 
# VacationPy

### Task
* Use jupyter-gmaps and the Google Places API to find the ideal vacation spot by:
  * Creating a heat map that displays the humidity for every city and then narrowing down to find the ideal weather condition (a max temperature lower than 80 degrees but higher than 70, wind speed less than 10 mph, zero cloudiness).
  * Using Google Places API to find the first hotel for each city located within 5000 meters of coordinates derived prior
  * Plotting the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
