# Vacation Weather Analysis

## Project Overview:
#

In this project, we generated 2000 random latitude and longitiude coordinates with the "np.random.uniform" method and combined them with the "zip" function to get lat/lng coordinate pairs around the world. With these generated coordinate pairs we used the citipy module's "citipy.nearest_city" function to find the nearest city to each of our coordinate pairs. We then used API's to collect current weather data in these cities to help prospective vacationers find a city and nearest hotel that met their weather criteria. A vacationer input box was created in the Itinerary for them to input their starting city as well as the three city stops they planned to make. Lastly, Google Maps API's was used to create a travel route between the four inputed cities.
#

## Results:

![WeatherPy_vacation_map](https://github.com/Brotherscodes/World_Weather_Analysis/blob/661f112b6a4acbc0331b24a5a7a9f92a0c8d774d/Images/Deliverable%202%20Map.png)

## Resources
- Data Sources: [https://openweathermap.org/api](https://openweathermap.org/api), 
https://mapsplatform.google.com/

- WeatherPy_Database.csv
- WeatherPy_vacation.csv
- Software: Jupyter Notebook/Lab, Pandas, CityPy, Python, APIs, JSON, Numpy