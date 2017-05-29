## Population-chloropleth time series

Goal: A Chloropeth map of population estimates for the counties in USA from the year 2010 to 2016, with an interactive by a scroll bar or something similar.

### Demo

https://bl.ocks.org/sabeehtaqi/fe4f3f2f8cf2c7ee82f5dca555aae1d3

### Data

Project repository: https://github.com/sabeehtaqi/FINAL-PROJECT

### Instructional demos

1. This demo shows how to read CSV data for the project into a map of counties for the entire US.

*  https://umbcvis.github.io/projects/sabeehtaqi/index.html

2. This demo modifies #1 in several ways.  But many things don't work quite right, and there's no legend.

*  https://umbcvis.github.io/projects/sabeehtaqi/index2.html

3. This demo modifies #2 by printing county names on mouseover.

*  https://umbcvis.github.io/projects/sabeehtaqi/index3.html


## To Do

Next steps for the project....

#### Documentation

##### Add links to all data sources

Data were downloaded in excel format. Several columns were not useful so the data were refined and converted to CSV

#### Technical

Starting with the instructional demo above [Mick Bostock's Chloropleth map](https://bl.ocks.org/mbostock/4060606):

1. Integrate census data
    * You'll need to adapt the demos to CSV data
        * Will need to construct 5-digit FIPS ID from the CSV data
2. For ideas on constructing the chloropleth map, look at this example...
    * https://bl.ocks.org/mbostock/4060606
    * Note: this examples uses a fancy approach to load the TSV data. The instructional demo already loads your CSV and may be easier to understand.
3. Add interaction somehow (TBD)

Note: For each step, create a separate gist/block -- link to these in your repo's README.md.
