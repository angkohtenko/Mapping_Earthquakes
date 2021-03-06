# Mapping Earthquakes
## Overview of the project

The purpose of the project was to build a map with earthquakes for the last 7 days. As a source of earthquakes data I used [earthquake.usgs.gov](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php).

To build a map I've used Leaflet JavaScript library.

## Result
I've written the script which retrives GeoJSON data with earthquakes from [earthquake.usgs.gov](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) and build markers for every earthquake on the map. Radius and color of the marker depends on the magnitude of the earthquake. Also, there is a popup for every marker with location and magnitude info.

![](https://github.com/angkohtenko/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/Images/Streets_view_popup.png)

As there are a lot of earthquakes on the map, to reduce cluttering I've created  additional layer for only major earthquakes with magnitude more than 4.5.

![](https://github.com/angkohtenko/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/Images/Major_earthquakes.png)

In addition, I've created a layer with tectonic plates based on the info from [github.com/fraxen/tectonicplates](https://github.com/fraxen/tectonicplates).

Also, I've created 3 tile layers to select: streets view, satellite and dark mode. All layers can be chosen from the menu at the upper left corner.

![](https://github.com/angkohtenko/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/Images/Dark_mode_Tectonic_plates.png)

