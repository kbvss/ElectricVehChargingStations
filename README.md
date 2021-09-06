# Electric Vehicle Charging Stations

Visualizing Electric Vehicle Charging Stations in Tennessee using QGIS.

# QGis Mapping Software link

https://www.qgis.org/en/site/

# Data Source

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


# Shapefile source for the state/country/province boundaries

https://www.naturalearthdata.com/downloads/50m-cultural-vectors/


# After adding the data to the map

I made sure to set the scale visibility for the layer as 1:500000000, so the points will plot at the correct location.

![ScaleVisi](https://github.com/kbvss/ElectricVehChargingStations/blob/main/ScaleVisibility.PNG?raw=true)


# The Completed Map


![MAPTN](https://github.com/kbvss/ElectricVehChargingStations/blob/main/Electric%20Vehicle%20Charging%20stations.png?raw=true)
