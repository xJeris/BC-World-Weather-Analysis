# World Weather Analysis
In this exercise we were tasked with collecting weather data for random cities and then creating a custom travel itinerary based on user input.

### Weather Database
Using the OpenWeatherMap API I created a dataframe of randomly selected cities. This included basic weather information about each city, as well as its name, country, and geolocation. I then exported the results to a .CSV file for use with my vacation search.

### Vacation Search
Using the city data I collected earlier, I created a location search based on a users input of the minimum and maximum desired temperature. After filtering the data based on temperature, I used the Google Maps API to find the nearest hotel for each city based on their geolocation.

### Vacation Itinerary
Using my updated location and hotel information I created a marker map showing the hotel name that was selected for each city. I then chose 4 cities to create a travel itinerary. Using the Google Maps Directions API, i created a route map. Finally, I created a marker map, showing the city and hotel information for my itinerary.
