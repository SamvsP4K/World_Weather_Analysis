# World Weather Analysis

The purpose of this analysis was to create an application that used both the weather api from openweathermap.org and the google maps api to get real time weather data to determine the best vacation spots.


## Requirements:

*The requirements for this application was a deliverable that included parsing through json information from the openweather api. The information retrieved from the requests were latitude and longitude, maximum temperature, humidity, cloudiness, wind speed, and finally weather description. 

*The second deliverable required creating a travel destination map. The map would take in two imputs from the user, the minimum temperature they would like on a vacation and the maximum. The application then uses weather information to determine which cities meet those requirements. A dataframe with each of those cities was created, which was cleaned up by droppping null values, and an interactive map with each city as a marker was included.

*Finally, the third deliverable was creating a vacation itinerary using the information gathered from deliverable two, which was the preferred cities. The google map directions api was used to pick cities and create an itinerary that was then mapped out for the "driving" option. See example below:


![Waypoints](https://user-images.githubusercontent.com/110923091/203158995-54955985-50e0-4559-af9a-5f3b08bf6dda.PNG)


Finally, a new marker layer map of the 4 cities chosen for the route was created.


![city_points](https://user-images.githubusercontent.com/110923091/203159248-7f618a65-77a2-4474-bf39-1ed25847e764.PNG)
