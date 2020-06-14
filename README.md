# python-api-challenge
API Homework

1) WeatherPy

Using cityPy, lat and long coordinates were picked at random and output cities and stored into a .csv.  The cities were used to get weather info from openweathermap.com.  

The following scatterplots were created to see if there are relationships between the latitude and the weather condition:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Further, the locations were split into northern and southern hemisphere to see if there were any additional patterns/relationships to uncover:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

2) VacationPy

From the above .csv, ideal weather conditions were used to filter the cities.  Google Maps was used to create a heat map.

Also, Google Places API was used to search cities with the ideal weather conditions for the closest hotel within 5000m.  Google Maps was used to create a map of hotel locations.
