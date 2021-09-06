# Electric Vehicle Charging Stations

Visualizing Electric Vehicle Charging Stations in Tennessee using QGIS. 

With society's shift towards sustainable energy, electric vehicles are slowly but surely becoming the norm on the roadway. As someone who commutes long distances to my workplace, I was curious to see how many stations were in Tennessee. Would there be enough to warrant long distance travel or the peace of mind to know that I could recharge my vehicle as needed?

# QGis Mapping Software link

https://www.qgis.org/en/site/

# Data Source

Electric Vehicle Charging Station Locations in the United States and Canada. 
https://afdc.energy.gov/fuels/electricity_locations.html#/analyze?fuel=ELEC

# Importing Open Street Map
Within the browser window right click "XYZ Tiles"
* Click New Connection
* Name it Open Street Map
* Click this URL to find the link to the Open Street Map servers https://wiki.openstreetmap.org/wiki/Tile_servers
* Use the Standard Tiles layer for Open street map: https://tile.openstreetmap.org/${z}/${x}/${y}.png. 
* Paste the URL
* Click okay

![XYZTileExample](https://github.com/kbvss/ElectricVehChargingStations/blob/main/XYZ%20tile%20example.png?raw=true)


# Shapefile source for the state/country/province boundaries -1:50m Cultural Vectors

"Admin 1 – States, provinces" was the shapefile used

https://www.naturalearthdata.com/downloads/50m-cultural-vectors/


# After importing the CSV file 

I made sure to set the scale visibility for the layer as 1:500000000, so the points will plot at the correct location.

![ScaleVisi](https://github.com/kbvss/ElectricVehChargingStations/blob/main/ScaleVisibility.PNG?raw=true)


# The Completed Map


![MAPTN](https://github.com/kbvss/ElectricVehChargingStations/blob/main/Electric%20Vehicle%20Charging%20stations.png?raw=true)


When I completed the map, I was surpised to see the amount of stations in Tennessee. If I were to make the shift to an electric vehicle, charging stations locations would be the least of my worries as there are plenty within a realistic distance from each other.
