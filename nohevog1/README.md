
## Benin agriculture

### Goal

Interactive map showing genetic diversity of rice varieties in two ecogeographic regions in BENIN, West Africa, 
and relationship to:
* management and decisions that farmers make on their fields on a daily basis, and
* environmental variables such as rainall, elevation, temperature, etc.
It will also display some touristic characteristics of the country and some points of interests.

##### Objectives

1. Display the different shapefiles
2. Overlay them 
3. Figure out the type of interactions among shapefiles
4. Would like to create an UII to display or not the different elements chosen from a drop-down list
5. Click on a Department or State, and have the different pictures showing and close
6. Make one or 2 graphs

### Project repository

https://github.com/nohevog1/Final_Project -- old data files (pre-projected coordinates)
https://github.com/nohevog1/Final_Project2 -- updated data files (un-projected coordinates)

Project to date: http://bl.ocks.org/nohevog1/717b70a117ee38e910cfa737ac86eb06

### Gists

1. https://gist.github.com/nohevog1/f4ce6e47ed1d2fb3cb96d3b4a43155b2

    * This gist is using the wrong URL for "Departements.json" -- see discussion forum

2. https://gist.github.com/nohevog1/56f18c2095fcd145b384cf01147042f7

    * This is a modified version of the slippy map [demo from Class 10](https://umbcvis.github.io/classes/class-10/).

### Instructional demos

1. This demo shows how to plot one of the GeoJSON files on a slippy map

    * https://umbcvis.github.io/projects/nohevog1

2. This demo make small changes to a gist that's in development.  The two sections of code that were changed have comments. The primary change: villages now appear on the map, and you can mouseover those villages to change the title. Nothing else was done.

    * https://umbcvis.github.io/projects/nohevog1/index2.html

## To Do

These are next steps for your project.

### Data Preparation -- IMPORTANT

You need to fix some of your shapefiles.  

The instructional demo (above) shows GeoJSON created from Africa.shp.  Africa.shp is "unprojected", meaning locations are stored as Latitude & Longitude. The same is true for Alibori_Villages_surveys.shp, which also works well.

However, other shapefiles in your repo use WGS_1984_UTM_Zone_31N -- these need additional work.

**You need to make sure all your shapefiles are "unprojected", as you've done for Africa.shp and Albori_Villages.shp**

### Technical

Modify your Gist #2 slippy map so that it starts zoomed in on Benin.

    * Change the initial center (line 87) and zoom level (line 96) to center the slippy map on Benin

### Documentation

Add the following content to the README.md in your project repo.

* Attribution -- Add (to **your** project repository) a sentence describing data source/ownership.
    * *If your data were created as part of another class or program, then reference that class/program*
* Extremely brief description of all pre-processing
    * *Did you create your shapefiles for your other class/program?  If so, what tools did you use?*
    * Shapefiles converted to GeoJSON by instructor: https://github.com/umbcvis/projects/tree/master/nohevog1

