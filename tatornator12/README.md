# Mars Landing Sites

The overall goal of the final project was to create an interactive globe of Mars that presented the location of previous landers on the surface in D3.js. This application would allow users to rotate, zoom, and hover over points for more information about a specific landing site location. This was all acheived using D3.js, but at the cost of zoom issues as well as performance and optimization (which you can see in the D3.js project site). Therefore, I was urged by my professor to recreate this project using a combination of Three.js and D3.js, which proved to be very successful with some minor cosmetic enhancements (as seen above in the Three.js project site).

## Demo

https://tatornator12.github.io/classes/final-project/Three.js_Version/

## Project Links

Project Repository: https://github.com/tatornator12/classes/tree/master/final-project

D3.js Version Project Site: https://tatornator12.github.io/classes/final-project/D3.js_Version/

Three.js Version Project Site: https://tatornator12.github.io/classes/final-project/Three.js_Version/

## Data

* Basemap of Mars - [USGS](https://astrogeology.usgs.gov/search/map/Mars/Viking/MDIM21/Mars_Viking_MDIM21_ClrMosaic_global_232m)
* Viking MDIM2.1 Colorized Global Mosaic 232m
* Landing Sites - [USGS - PIGWAD (deprecated)](ftp://pdsimage2.wr.usgs.gov/pub/pigpen/mars/Nomenclature/)
    * Converted from a Shapefile to GeoJSON
    * Updated additions (Mars 3, Beagle 2, and Mars Polar Lander) of failed missions from [Planetary.org](http://www.planetary.org/multimedia/space-images/charts/mars_landing_site_map_lakdawalla.html)
        
* D3.js Version
    * Versor.js from Mike Bostock's [Versor Dragging](https://bl.ocks.org/mbostock/7ea1dde508cec6d2d95306f92642bc42)
      
* Three.js Version
    * Title font and layout inspired by [100,000 Stars](https://www.chromeexperiments.com/experiment/100000-stars)
    * Atmosphere Shader from [Stemkoski](https://github.com/stemkoski/stemkoski.github.com/blob/master/Three.js/Shader-Halo.html)
    * Starfield from [Threejs.org](https://threejs.org/docs/index.html#api/materials/PointsMaterial)
    * D3 GeoJSON from Mike Bostock's [GoeJSON in Three.js](https://bl.ocks.org/mbostock/2b85250396c17a79155302f91ec21224)
    * MouseOver Event from [Stemkoski](https://github.com/stemkoski/stemkoski.github.com/blob/master/Three.js/Mouse-Over.html)

## Gist Links

1. D3.js-only Version: https://gist.github.com/tatornator12/b486e2fef1039cdcc321c4c1fbdf329a
2. Three.js Version using WebGL and D3.js: https://gist.github.com/tatornator12/be3bdfade7f23212440fbd2a93e835c4
