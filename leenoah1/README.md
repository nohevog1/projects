## Anacostia Watershed

Purpose/Goals: Create interactive webmap of census demographic data in the Anacostia Watershed

### Demo

https://leenoah1.github.io/class_project

### Project repository

https://github.com/leenoah1/class_project

**Data sources**

* Link to Anacostia Watershed data from MWCOG (current employed organization. Data used to clip to census.gov tract data): http://www.anacostia.net/maps/Data_download.html
* Maryland census tract data from census.gov: https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2010&layergroup=Census+Tracts

**Brief Description of Geoprocessing:**

* clipped Anacostia watershed shapefile to census.gov Maryland tract shapefile
* recalculated population demographics of new tracts that were clipped by the watershed shapefile
* calculated new geometry (acres)
* calculated new population numbers based on new tract geometry/area

## Instructional demo

This demo shows how to read and plot the watershed topojson.  Examination of the plot shows that the clipping process (accomplished when creating the shapefiles) has introduced some errors in the topology.

* https://umbcvis.github.io/projects/leenoah1/index.html

## To Do

For each step, create a separate gist/block -- link to these in your repo's README.md

1. Plot GeoJSON -- put it in a gist and link to it from your repo's README.md
2. Plot GeoJSON on top of the slippy map (zoomable map tiles) from the Class 12 demo
3. Add interaction using data in the GeoJSON file

If all goes well with these steps, consider using Leaflet...

*  leaflet gist: https://gist.github.com/leenoah1/c6cb58257f6069bfb9d1d305df36e621

