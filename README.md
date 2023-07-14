# Inverloch's Marine Habitats - Interactive Map

This repository contains a demonstration of how to create a simple interactive map of marine coastal habitats using Python code inside a Jupyter Notebook.

The area chosen for this case study is the coastline surrounding the town of Inverloch in Victoria, Australia. Three datasets are used in this study:
- A Zone of Interest, defined by drawing a 5km bufferzone around the postcode boundaries of Inverloch.
- The Statewide Marine Habitat Map 2023, produced by the State Government Department of Energy, Environment and Climate Action (DEECA) clipped by the Zone of Interest. 
- Victorian Coastal Nearshore Bathymetry 20m resolution DEM 5m Contours, also clipped by the Zone.

The latter two datasets were sourced from [DEECA's Datashare Platform](https://datashare.maps.vic.gov.au/).

Below is a quick and simple demonstration of how to use the map once loaded:

![map demo](images/map_demo.gif)

If you wish to reproduce the steps outlined in the Jupyter Notebook locally, it is best advised to use the Dockerfile to build a container in VS Code or your chosen IDE once you've cloned this repository. 