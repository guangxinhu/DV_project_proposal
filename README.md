# Data Visualization Project

## Data

The data I propose to visualize for my project is an earthquake data.</br>

The origin of database is [National Geophysical Data Center / World Data Service (NGDC/WDS): Significant Earthquake Database. National Geophysical Data Center, NOAA.](https://www.ngdc.noaa.gov/nndc/struts/form?t=101650&s=1&d=1).</br>

The Significant Earthquake Database contains information on destructive earthquakes from 1970 to the present that meet at least one of the following criteria: Moderate damage (approximately $1 million or more), 10 or more deaths, Magnitude 7.5 or greater, Modified Mercalli Intensity X or greater, or the earthquake generated a tsunami.


## Prototypes

I’ve created a proof of concept visualization of this data. </br>

Each point represents an earthquake event.</br>

The x-coordinate represents the different years, and the y-coordinate represents the earthquake magnitude. The color of circle indicates the duration of earthquake.

![image](https://user-images.githubusercontent.com/37562094/66102481-81564500-e580-11e9-8ea6-4d6bece3957e.png)

## Sketches

The visualization of global earthquake datasets is mainly presented in the following figure. A heat map is planned to show the frequency of earthquakes around the world based on statistical data, and each earthquake event will also be displayed as scatter plot on the map.

![image](https://user-images.githubusercontent.com/37562094/66104371-5c64d080-e586-11e9-8b41-4891a478a0d5.png)
(resource: http://npdp.stanford.edu/eq_historical_catalog)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which areas are prone to earthquakes, which areas do not often occur in the earthquake.
 * Which places are prone to high magnitude earthquakes.
 * Which places are prone to earthquakes of longer duration.
 * The occurrence and distribution of important earthquakes around the world in different years.
 * Which earthquake triggered the Tsunami.
 * If I can, try to realize 'zoom' function for map.

## Schedule of Deliverables

* Prepare geospatial data and make a world map with React & D3.
* According to earthquake statistical data, color different region in different colors.
* Mark each earthquake event on the map by scatter plot.
* Creat timeline bar to show earthquake situation among years.(interaction)
* Polish final project.

## Open Questions
 *
