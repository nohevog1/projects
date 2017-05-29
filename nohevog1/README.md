
# Benin agriculture / Benin ecotourism

## Goal

Interactive map showing genetic diversity of rice varieties in two ecogeographic regions in BENIN, West Africa, 
and relationship to:
* management and decisions that farmers make on their fields on a daily basis, and
* environmental variables such as rainall, elevation, temperature, etc.
It will also display some touristic characteristics of the country and some points of interests.

### Objectives

1. Display the different shapefiles
2. Overlay them 
3. Figure out the type of interactions among shapefiles
4. Would like to create an UI to display or not the different elements chosen from a drop-down list
5. Click on a Department or State, and have the different pictures showing and close
6. Make one or 2 graphs

#### Project repository

https://github.com/nohevog1/Final_Project -- old data files (pre-projected coordinates)
https://github.com/nohevog1/Final_Project2 -- updated data files (un-projected coordinates)

##### Instructional demos

1. This demo shows how to plot one of the GeoJSON files on a slippy map

    * https://umbcvis.github.io/projects/nohevog1

2. This demo make small changes to a gist that's in development.  The two sections of code that were changed have comments. The primary change: villages now appear on the map, and you can mouseover those villages to change the title. Nothing else was done.

    * https://umbcvis.github.io/projects/nohevog1/index2.html

###### To Do (Data Preparation & Technical) 

These are next steps for your project.
   
   ** Data Preparation
   
You need to fix some of your shapefiles.  

The instructional demo (above) shows GeoJSON created from Africa.shp.  Africa.shp is "unprojected", meaning locations are stored as Latitude & Longitude. The same is true for Alibori_Villages_surveys.shp, which also works well.

However, other shapefiles in your repo use WGS_1984_UTM_Zone_31N -- these need additional work.

------You need to make sure all your shapefiles are "unprojected", as you've done for Africa.shp and Albori_Villages.shp------

   ** Technical

Modify your Gist #2 slippy map so that it starts zoomed in on Benin.

    * Change the initial center (line 87) and zoom level (line 96) to center the slippy map on Benin

###### Documentation

See here: https://github.com/nohevog1/Final_Project2/blob/master/README.md
    
###### Final Project Final Version

The project ended up being more of a touristic map of BENIN. The map is an overlay of 9 different layers. The map shows national parks, cynegetic zones, the 12 departments of the country, but also some data about my doctoral research such as the communes or subdivisions in the North and the South of the country as well as the different villages in which I conducted my doctoral field research. 
For more information on my doctoral research, please visit: http://nohemivoglozin.wixsite.com/nohemi-voglozin/projects.

The map allows the user to add or remove some layers, and when the user hover on the villages, the names are displayed as an info, and on the other layers, pictures representing a particularity of the region is shown along with the name of the feature.

FINAL PROJECT GIST: https://gist.github.com/nohevog1/7e9f3a0a170cd644cbd020f94ba9aa39

FINAL PROJECT DEMO: http://bl.ocks.org/nohevog1/raw/d978718d7bb6f7479dbe7a00c2db1eaf/

