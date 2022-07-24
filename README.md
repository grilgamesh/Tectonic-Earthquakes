# leaflet-challenge
week 15 Homework


This repo works through the requirements of the homework and completes some of the bonus activities.

The JS file creates several layers initially, in order for users to have access to a street map or a (more useful in my opinion) topographic map. The default view centres on the Pacific Rim.

The code then renders the key to the colour system, using a defined function for consistency.

It take the GeoJson data through D3 and loops through the list of earthquakes inside the response. For each earthquake, a circle is generated from latititude, longitude, depth, and magnitude.