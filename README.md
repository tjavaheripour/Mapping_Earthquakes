# Mapping_Earthquakes

Here, we built insightful data visualizations with interactive features on earthquakes from around the world.
We traversed and retrieved the earthquake data using JavaScript and the D3 and leaflet libraries and plot the data on a Mapbox map through an API request. On the map, the magnitude and location of each earthquake is shown in a popup marker. The diameter of the markers for each earthquake reflects the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color with a legend providing the context for our map data. Then, to illustrate the relationship between the location and frequency of seismic activity and tectonic plates we added fault lines on the map.
Finally, 
1.	We add tectonic plate data using **d3.json()**, add the data using the **geoJSON()** layer as a second layer group, set the tectonic plate **LineString** data to stand out on the map, and add the tectonic plate data  to the overlay object with the earthquake data.
2.	We add major earthquake data as a third layer group to the map using **d3.json()**, and a color and set the radius of the circle based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, **geoJSON()**.
3.	We add a third map style **(navigation-night)** to the earthquake map.

![night.PNG](https://github.com/tjavaheripour/Mapping_Earthquakes/blob/main/night.PNG)
