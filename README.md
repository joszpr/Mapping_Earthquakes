# Mapping_Earthquakes

### Summary ### 

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. 

Using JavaScript and D3, a URL was called to the U.S. Geological Survey (USGS) website in order to retrieve GeoJSON data about all earthquakes registered for the last seven days. The geographical coordinates and magnitudes of the earthquakes were extracted and, utilizing the Leaflet library, they were potted on an interactive Mapbox map through an API request. 

The interactivity of the map was further developed in order to contain 3 different types of maps from Mapbox; Street View, Satellite Streets View and Dark View. 3 different layers were added; All Earthquakes for the past 7 days, Tectonic Plates lines, and Major Earthquakes for the past 7 days (4.5 or greater in magnitud). The tectonic plates lines were gathered from an open source repository of Github user fraxen.    


### Resources ###
JavasScript, D3 Library, Leaflet Library. 

**Mapbox Maps**
https://www.mapbox.com/

**USGS Earthquakes API**
https://earthquake.usgs.gov/

**Tectonic Plates data** 
https://github.com/fraxen/tectonicplates
Updated digital model of plate boundaries by Peter Bird (Geochemistry Geophysics Geosystems, 4(3), 1027, [doi:10.1029/2001GC000252]
(http://scholar.google.se/scholar?cluster=1268723667321132798), 2003).
