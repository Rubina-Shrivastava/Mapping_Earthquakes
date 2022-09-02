# Mapping_Earthquakes
## Purpose
### The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days,to complete this project we use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.
## Result:
### The map visualization can be viewed and interacted with in its entirity here.Each earthquake is visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake. The map has three views:
### Street View
### Satellite View
### Dark View
## Summery:
### To complete this project, we use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then we can see the earthquake data in relation to the tectonic plates’ location on the earth, and the earthquakes with a magnitude greater than 4.5 on the map,  the data on a third map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts are built using JavaScript and D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We then used Leaflet library to plot the data on a Mapbox style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display Tectonic plates, Earthquake magnitude and location information.