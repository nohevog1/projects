# Maryland county

Interactive chloropleth map based on data from census.gov

The Goal is to identify the counties with the greatest population.
The chart will show how the population is distributed by age cohorts, which
will tell the story as to what age cohorts are concentrated in specific Counties, e.g., PG County has the largest population ages 20-24, perhaps because of UMD, and Montgomery County seems to attract retirees.

### Demo

https://bl.ocks.org/MTClass/ac07c1f5e40ead6930c32a4a0e2ae67a

### Data

Project repository: https://github.com/MTClass/Project

Data are from census.gov, both the decennial census and American Fact Finder.

    * https://www.census.gov/data/developers/data-sets/acs-5year.2015.html

### Instructional demos

1. Using the [Class-23 demo](https://umbcvis.github.io/classes/class-12) as a starting point,
this demo shows how to reconstruct all the counties from the census tracts.
    * https://umbcvis.github.io/projects/mtclass/index.html
2. Starting from [this gist](https://gist.github.com/MTClass/65b5751166dbf5a32a70bf47e41e4a00), the following demo shows how to display the county FIPS when dragging the big yellow ball over the map. This should help answer the question posed in the forum on 5 May.
    * https://umbcvis.github.io/projects/mtclass/index2.html
3. Starting from [this gist](https://gist.github.com/MTClass/d8b6c866f20730e572da366589e99a14), 3 changes are made to create custom X-axis labels. 
    * https://umbcvis.github.io/projects/mtclass/index3.html
    * See [MDN API docs](https://developer.mozilla.org/en-US/docs/Web/SVG/Element/text) for more info on SVG text formatting.

#### To Do

* Get the map and (one of the) charts to interact 
