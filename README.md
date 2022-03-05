# Mapping_Earthquakes

## Purpose
Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

## Resources
#### Data Sources: 
* tectonic_plate_starter_logic.js
* index.html
#### Data Tools: 
* JavaScript
* JSON, GeoJSON
* IO (Web Server)
#### Software: 
* ES6+
* ECMAScript
* Visual Studio Code 1.50.0

## This new assignment consists of three technical analysis deliverables. I will submit the following:

* Deliverable 1: Add Tectonic Plate Data
* Deliverable 2: Add Major Earthquake Data
* Deliverable 3: Add an Additional Map

# Deliverable 1 Requirements: 
* The tectonic plate data is added as a second layer group
* The tectonic plate data is added to the overlay object
* The d3.json() callback is working and does the following:
  * The tectonic plate data is passed to the geoJSON() layer
  * The geoJSON() layer adds color and width to the tectonic plate lines
  * The tectonic layer group variable is added to the map
* The earthquake data and tectonic plate data displays on the map when the page loads

### [Code Located Here](https://github.com/tonjakae/Mapping_Earthquakes/blob/main/tectonic_plate_starter_logic.js)

![image](https://user-images.githubusercontent.com/87340105/156868692-e5d8139d-ef0e-4d7b-b7a7-c8e0337b7214.png)

# Deliverable 2 Requirements:
* The major earthquake data is added as a third layer group
* The major earthquake data is added to the overlay object
* The d3.json() callback is working and does the following:
  * Sets the color and diameter of each earthquake.
  * The major earthquake data is passed to the geoJSON() layer.
  * The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
  * The major earthquake layer group variable is added to the map
* All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off

# Deliverable 3 Requirements:
* A third map tile layer is created
* The third map is added to the overlay object
* All the earthquake data and tectonic plate data are displayed on the all maps of the webpage

![image](https://user-images.githubusercontent.com/87340105/156869080-4cd20344-8c2b-4f35-928c-49ae845e7b03.png)

![image](https://user-images.githubusercontent.com/87340105/156869091-97855e74-df1e-425a-b525-fe6d026d536c.png)







