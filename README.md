# SolarPanel

Citations:

1. Google Maps API - To display the map and customize polygons
2. Calculating area of the polygon idea inspired from here - https://stackoverflow.com/questions/12671077/calculate-area-of-a-drawn-polygon-on-google-map-javascript

Assumptions:

1. User is going to draw one polygon at a time and is going to delete the already drawn one before drawing the next one. This makes the experience smooth and straight forward.
2. The first version of the product doesn't have polygon editing capabilities. It can be added in the next release and the area will be updated real time with the size.

Nominal Power:

This can be calculated using the area of the drawn solar panel.
Light intensity = 1000 W/m2
Latitude = 35°N
Airmass = 1.5
Temperature = 25 °C

Running the code:

1. Download all the files from the repository to your local.
2. Open the index.html in your browser and start searching and drawing the polygon.