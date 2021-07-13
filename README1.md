# Mapping_Earthquakes
Using APIs to create interactive maps displaying location and magnitude of earthquakes using GeoJSON data
## Data Citation
The Earthquake data is from [earthquake.usgs.gov](https://earthquake.usgs.gov/).
Map API calls are processed from [Mapbox](https://www.mapbox.com/).
[Leaflet](https://leafletjs.com/) is the JavaScript library used to format the API information.
## Overview
The goal of the project was to create an interactive map showing earthquake data from the past 7 days. The JavaScript code is in the [challenge_logic.js](https://github.com/RuthLD/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js) file and the HTML code for the site is in the [index.html](https://github.com/RuthLD/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html) file.
### Map Views
There are three options for the base map that can be changed by the user. ![Change_Map.gif](https://github.com/RuthLD/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Change_Map.gif).
### Map Layers
There are three layers that can be selected to show any combination of data related to the earthquakes. ![Change_Layer.gif](https://github.com/RuthLD/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Change_Layer.gif)
### Earthquake Data
The magnitude and location of the earthquake can be viewed as a popup by clicking on the circle marker for the earthquake. ![Popup.png](https://github.com/RuthLD/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Resources/Popup.png)
