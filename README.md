# Vacation Weather Analysis

## Project Overview:
#

In this project, we generated 2000 random latitude and longitiude coordinates with the "np.random.uniform" method and combined them with the "zip" function to get lat/lng coordinate pairs around the world. With these generated coordinate pairs we used the citipy module's "citipy.nearest_city" function to find the nearest city to each of our coordinate pairs. We then used API's to collect current weather data in these cities to help prospective vacationers find a city and nearest hotel that met their weather criteria. A vacationer input box was created in the Itinerary for them to input their starting city as well as the three city stops they planned to make. Lastly, Google Maps API's was used to create a travel route between the four inputed cities.
#

## Results:

![WeatherPy_vacation_map](https://github.com/Brotherscodes/World_Weather_Analysis/blob/661f112b6a4acbc0331b24a5a7a9f92a0c8d774d/Images/Deliverable%202%20Map.png)

![csv_output_weatherpy_vacation](https://github.com/Brotherscodes/World_Weather_Analysis/blob/f600358d3175d4911bf2dc9ae132471d7cb5db06/Images/WeatherPy_Vacation.csv%20screenshot.png)


Our code generated 748 cities using the "citipy.nearest_city" method which we then converted into a DataFrame with the above output. 

### Travel Itinerary and Google Maps Directions API'S:

![png_output_weatherpy_travel_map](https://github.com/Brotherscodes/World_Weather_Analysis/blob/f600358d3175d4911bf2dc9ae132471d7cb5db06/Images/WeatherPy_travel_map.png)

![png_output_travel_map_markers](https://github.com/Brotherscodes/World_Weather_Analysis/blob/f600358d3175d4911bf2dc9ae132471d7cb5db06/Images/WeatherPy_travel_map_markers.png)

Using the CSV file containing the list of cities we found the nearest hotel and used Google Maps API's to create a travel route reommendation for our vacationer to include their four selected cities.

## Resources
- Data Sources: [https://openweathermap.org/api](https://openweathermap.org/api), 
https://mapsplatform.google.com/

- WeatherPy_Database.csv
- WeatherPy_vacation.csv
- Software: Jupyter Notebook/Lab, Pandas, CityPy, Python, APIs, JSON, Numpy