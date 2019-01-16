
## WeatherPy
*J. R. Peel*

I have created a Python script to analyze the weather of 500 cities. The data presented here describes the weather on January 2nd, 2019.

*Results*

A total of 600 coordinates were randomly generated, corresponding to 600 cities (cities.csv). Api requests were made for all 600 cities. Given that not all cities produce weather data, a sample of 500 of those cities was choosen and mapped (weather_data.csv).
There are more cities between 60° and 90° degrees latitude, than betwenn -90° and -60°, due to the presence of landmass, while there are less cities towards the south pole (-90°) given that there is less habited land mass, being the largest in this region Antarctica. 
Figure 1 shows the relationship between temperature (°F) and latitude. Temperature showed a bell shaped distribution. Higher temperatures were observed in the southern hemisphere (-90° to 0°), because the southern hemisphere currently experiences summer conditions, while the northern hemisphere (0° to 90) currently experiences winter conditions, showing lower temperatures. The highest temperatures were observed in latitudes between -20° and -°40. Most of the world’s deserts are found at latitudes around 30° on both sides of the equator and could therefore explain the observed temperature peak at around -30°. Freezing temperatures (32°F) were only observed at latitudes higher than 20°. Most of the tropical region (-30° to 30° latitude) showed temperatures above 40°F. 

![](https://github.com/JoannePeel/What-s-the-weather-like-/blob/master/Lat_Temp.png) 
Fig. 1. Temperature (°F) vs latitude.

Figure 2 shows the relationship between humidity and latitude. The lowest humidity values were observed between 20° and 40° on both sides of the equator (0°), which may be associated with the presence of major deserts in this area. 

![](https://github.com/JoannePeel/What-s-the-weather-like-/blob/master/Lat_Hum.png)
Fig. 2. Humidity (%) vs latitude.
Figure 3 shows cloud cover related to latitude. Cloud cover didn’t show any specific latitudinal trend.
 
![](https://github.com/JoannePeel/What-s-the-weather-like-/blob/master/Lat_Cloud.png)
Fig. 3. Clouds vs latitude.

Figure 4 shows wind speed in relationship to latitude. There was no trend observable regarding wind speed and latitude, although winds tend to be stonger towards the poles, given increased Coriolis forces.

![](https://github.com/JoannePeel/What-s-the-weather-like-/blob/master/Lat_wind.png)
Fig. 4. Wind speed vs latitude.

*Conclusions* 

There are more cities between 60° and 90° in the northern hemisphere than in the southern hemisphere.
The temperature gradient is generally bell shaped, with the hump located around the equator, however, the northern hemisphere is currently experiencing winter conditions, so temperatures are lower in the northern regions. The highest temperatures may be associated to the presence of major deserts around -30° latitude.
The lowest humilities were also observed around 30° on both sides of the equator, which may also be associated with the presence of desert regions.

