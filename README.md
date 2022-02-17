# World_Weather_Analysis

## Purpose
### The purpose of the world weather analysis is to enhance the PlanMyTrip app to take it to the next level. Users will be able to filter the data for their weather preferences to identify potential travel destinations, then choose four cities to create a travel itinerary. Then, using the Google Maps Directions API, a travel route between the four cities will be provided with a marker layer map.

## Retrieving the Weather Data
#### To retrieve the Weather Data, we connected to the weather_api_key to get the data for our randomly generated latitudes and longitudes. We added the current description to the data and added it to a new dataframe called "city_data_df". Then we created the output file to a CSV name WeatherPy_Database to use throughout the rest of our analysis.
<img width="802" alt="Screen Shot 2022-02-16 at 10 06 31 PM" src="https://user-images.githubusercontent.com/94096530/154415560-4934bd5c-2834-40e5-9540-d54c5ad739a7.png">


## Customer Travel Map
#### Once the customer gives their minimum and maximum weather preferences, potential travel destinations were provided along with the current description of weather. From there, the customer could narrow down the location that fits their weather preferences the best.
<img width="728" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/94096530/154417468-d84245d0-5366-482e-b2b7-bba3390c8be3.png">

## Travel Itinerary Map
#### Lastly, using the Google Directions API, the user could choose up to four destinations they wanted to travel to. Then after choosing their travel mode, a travel itinerary and map with markers is provided to the user. This map shoes the destinations they have identified for each stop, and shows the best route. In this case, the user's travel mode is driving.
<img width="738" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/94096530/154412550-eb2281ed-f2cc-4cda-b3e4-71b111a85066.png">
