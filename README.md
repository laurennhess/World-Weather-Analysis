# World_Weather_Analysis

## Purpose
### The purpose of the world weather analysis is to enhance the PlanMyTrip app to take it to the next level. Users will be able to filter the data for their weather preferences to identify potential travel destinations, then choose four cities to create a travel itinerary. Then, using the Google Maps Directions API, a travel route between the four cities will be provided with a marker layer map.

## Retrieving the Weather Data
#### To retrieve the Weather Data, we connecred to the weather_api_key to get the data for our randomly generated latitudes and longitudes. Then, we added the data to a new dataframe called "city_data_df" and created the output file to a CSV name WeatherPy_Database.
<img width="784" alt="Screen Shot 2022-02-16 at 9 34 02 PM" src="https://user-images.githubusercontent.com/94096530/154412007-673dbd34-663e-42fb-a5b2-2b2219007f11.png">

## Customer Travel Map
#### Once the customer gives their minimum and maximum weather preferences, potential travel destinations were provided were the current description field being the max temperature. From there, the customer could narrow down the location that fits their weather preferences the best.
<img width="742" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/94096530/154412383-c37914d8-12de-4231-a70e-6bf58c951346.png">

## Travel Itinerary Map
#### Lastly, using the Google Directions API, the user could choose up to four destinations they wanted to travel to. Then after choosing their travel mode, a travel itinerary and map with markers is provided to the user. This map shoes the destinations they have identified for each stop, and shows the best route. In this case, the user's travel mode is driving.
<img width="738" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/94096530/154412550-eb2281ed-f2cc-4cda-b3e4-71b111a85066.png">
