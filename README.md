# DashboardLab

## Public WiFI Locations around the city of Pittsburgh


### Purpose:
The purpose of this code is to address and highlight some of the issues surrounding digital equity, particularily in urban areas such as Pittsburgh. As tech continues to grow at an exponential rate, the access to internet becomes significantly important for citizens to be in the participating pool within the digital society. By creating a dashboard that highlights public WiFi locations in Pittsburgh, I aimed to bridge the gap by conveying essential information behind public WiFi.


### Libraries Used:
- Chart.js: for making interactive charts
- Mapbox GL: for displaying the basemap and geojson features
- D3.js: for data manipulation and visualization
- C3.js: for creating charts that are customizeable.


### JavaScript Functionality:
- Initializes the Mapbox Map with a dark theme and default center coordinates for Pittsburgh
- Implements a toggle functionality to show/hide the dashboard
- Loads Public Wi-fi data from a GeoJSON file and shows the different locations as proportional symbols
- Generates line charts based on the properties of the WiFi locations, such as locational details, as well as public notes

