# World_Weather_Analysis

Project Overview
PLANMYTRIP is a top travel technology company that specializes in internet-related services in the hotel and lodging industry. My role here is to collect and present data for customers via the search page, which they will then filter based on their preferred travel criteria in order to find their ideal hotel, anywhere in the world.

Purpose
Travel and tourism offer individuals a glimpse of the world. Weather conditions influence travel behavior and impact overall travel experience. The purpose of this project is to collect, analyze and visualize weather data across cities worldwide and to provide travelers with a tool that will allow them to determine their travel destination based on weather conditions.

Weather Database
A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.

The following data was retrieved from the API call:

Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Weather description(for example, clouds, fog, light rain, clear sky)
Vacation Search
Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations based on travelers’s preferences to identify potential travel destinations and nearby hotels. Each destination on the map would display the following data :

The city name
The country code
The weather description
The point’s size should be the maximum temperature for the city
Vacation Itinerary
I use Geoapify Routing API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, a map is created a pop-up marker for each city on the itinerary.
