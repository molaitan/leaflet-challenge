# leaflet-challenge
Leaflet HW - #15 Visualizing Data with Leaflet

This assignment required using the United States Geological Survey, USGS, earthquake data to create a visualization in the form of plots on a map using Leaftlet. 

Leaflet-Step-1:
The data set used for the Step 1- Basic Visualization was the "All Earthquakes from the Past 7 Days".  The data is given as a JSON representation and thus, pulled the data in using the URL provided on the USGS website. 

All Earthquakes from the Past 7 Days:
https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson

The end result is a map with data markers that reflect the magnitue of the earthquake by their size and depth of the earthquake by color. High magnitudes are larger in scale and earthquakes with greater depth are depicted as red in color. See legend.

There are popups that provide addtional information such as the magnitude, depth, and location when clicked. 

<img width="1355" alt="Screen Shot 2022-04-25 at 11 42 26 PM" src="https://user-images.githubusercontent.com/94502554/165216594-3e994c69-bd3d-492d-a64f-9929b5a3e7c8.png">

Leaflet-Step-2:
For the 2nd visualization, more data is added to the map to illustrate the relationship between tectonic plates and seismeic activity. The 2nd data set was pulled in from https://github.com/fraxen/tectonicplates.

The data was incorporated onto the existing default map, using json file from Leaflet-Step-1 by using geoJSON and D3. The 3 additional layers of base maps were added: grayscale, watercolor, and topography. The base layers can be turned on and off independently. Layer controls allow the ability to use toggle between the earthquake and tectonic plates data as well as teh several base layers. 

The final interactive map is shown below:

<img width="1342" alt="Leaflet-Step-2" src="https://user-images.githubusercontent.com/94502554/165217881-abb3f4cb-3cd7-4e68-9a83-44c52bfb8006.png">
