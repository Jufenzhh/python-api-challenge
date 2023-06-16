# python-api-challenge
Starting with the WeatherPy.ipynb script and OpenweatherMap API retreives weather data for a list of cities. 
Using OpenweatherMap API, data such latitude, longitude, temperature, humidity, cloudiness, windspeed, country, and date for each city is collected. 
The script creates scatter plots to the visual the relationships of latitude against weather parameters such as temperature, humidity, cloudiness, and wind speed. Each plot is saved as Png Image. 
The code creates linear regression analysis to examine correlation of latitude against the same weather parameters seperated in the Northern and Southern Hemispheres by plotting the regression line on scatters plots. The figures are saved in the same directory as WeatherPy.ipynb 

For VacationsPy.ipynb the script uses the datasets from the previous WeatherPy.ipynb and the Apis of Openweather Map and Geoapify. Geoapify is used to retreive weather parameters but mainly hotel names. 
The script creates a map to perform weather analysis for in each city. 
Then create new data frames to store data from and find ideal weather conditions, and a store of information for hotel names for the Geoapify Api. 
Using the new data_frames, and the Geoapify find nearby hotels then add the new information as hover information for map. 
