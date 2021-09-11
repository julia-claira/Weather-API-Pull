# Weather-API-Pull: Analyzes equator impact on weather patterns in northern and southern hemispheres 

### Part I - WeatherPy:
The aim is to create a representative model of weather across world (500+) cities.The Python script utilizes python library, citypy,  makes API calls to OpenWeatherMap to retrieve weather data. 

<img src="https://github.com/julia-claira/Weather-API-Pull/blob/main/output_data/fig6_linear_S_city_lat_vs_max_temp.png">

The first objective is to build a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

<img src="https://github.com/julia-claira/Weather-API-Pull/blob/main/output_data/fig12_linear_N_city_lat_vs_wind_speed.png">

The next objective is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 

