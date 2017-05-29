## New York demographics

Chloropleth Map of New York showing the Population under age  5 in all New York counties for years 2010-2015 based on data from census.gov.
The goal is to identify the counties by a color scheme and showing the percentage of population in a specific county.According to the data from census.gov Jefferson County has the highest population and Hamilton county has the least amount of population.

### Demo

https://bl.ocks.org/qaisarmehmood/4a8b618753d845694774aeb7b62a71ff

### Project repository

* https://github.com/qaisarmehmood/umbcvis

* Data: https://github.com/qaisarmehmood/umbcvis/blob/master/Newyork.population%20Data.csv

### Instructional demos

1. This demo shows how to read CSV data for the project into a map of counties for the entire US.

    *  https://umbcvis.github.io/projects/qaisarmehmood

2. The second demo shows how to filter all the counties except those in New York.  And it uses the [SVG transform attribute](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/transform) to zoom in on the state.

    *  https://umbcvis.github.io/projects/qaisarmehmood/index2

3. The third demo shows how to create a D3 map so that the CSV data can be queried by FIPS code.  The several lines of new code are indicated by "NEW" comments.  To see what's going on, you should open the developer console and scroll over some of the counties.

    *  https://umbcvis.github.io/projects/qaisarmehmood/index3

## To Do

#### Documentation

Add the following content to the README.md in your repo.

1. Attribution and links to all data sources
2. Extremely brief description of all pre-processing

#### Technical

For each step, create a separate gist/block -- link to these in your repo's README.md

1. Create plot of NY Counties based on us-atlas (if starting from one of Mike Bostock's blocks, provide a link)
2. Integrate data from census.gov to create chloropleth map using FIPS
3. Add interactive capability


