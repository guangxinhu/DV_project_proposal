# Data Visualization Project

## Data

The data I propose to visualize for my project is an earthquake data.</br>

The origin of database is [National Geophysical Data Center / World Data Service (NGDC/WDS): Significant Earthquake Database. National Geophysical Data Center, NOAA.](https://www.ngdc.noaa.gov/nndc/struts/form?t=101650&s=1&d=1).</br>

The Significant Earthquake Database contains information on destructive earthquakes from 1970 to the present that meet at least one of the following criteria: Moderate damage (approximately $1 million or more), 10 or more deaths, Magnitude 7.5 or greater, Modified Mercalli Intensity X or greater, or the earthquake generated a tsunami.


## Prototypes

### Scatter Plot

I’ve created a proof of concept visualization of this data. </br>

Each point represents an earthquake event.</br>

The x-coordinate represents the different years, and the y-coordinate represents the earthquake magnitude. The color of circle indicates the duration of earthquake.

![image](https://user-images.githubusercontent.com/37562094/66102481-81564500-e580-11e9-8ea6-4d6bece3957e.png)

### Map Plot

In addition to simply representing seismic data in a coordinate system based on numerical values, mapping seismic data on a map can give people a more intuitive sense of earthquake distribution. Therefore, the visualization effect of the whole data can also be observed with the knowledge of the location of the seismic belt.
![image](https://user-images.githubusercontent.com/37562094/67918776-1fcfc900-fb74-11e9-988b-e3fbdeb85661.png)

## Final Visualization

### Scatter Plot

For an earthquake, people often focus on the magnitude and focal depth of the earthquake. Unlike many post-earthquake loss data, these two data can most intuitively and quickly reflect the earthquake situation. Therefore, I choose to complete drop down box in data visualization to facilitate observation of the respective relationship between the year of the earthquake, the magnitude and focal depth. In addition, earthquake-prone areas are likely to generate tsunamis, and this scatter diagram shows which is more likely. As can be seen from the diagram, it is obvious that a large earthquake is more likely to trigger a tsunami.

![image](https://user-images.githubusercontent.com/37562094/67919100-535f2300-fb75-11e9-8c22-876d5c39f816.png)

### Earthquake Map

According to the location of each earthquake, we can map the occurrence of earthquakes on the world map, so as to get a more intuitive sense of which regions are more prone to major earthquake disasters. It can also give a more intuitive sense of whether earthquake-prone areas are the boundaries of continental plates. The larger the scatter radius in the figure is, the deeper the focal depth of the earthquake is.

![image](https://user-images.githubusercontent.com/37562094/67919015-172bc280-fb75-11e9-9dd1-13872185396c.png)

If one of no-tsu or Tsunami is selected, only the distribution of earthquake data that caused or did not cause a Tsunami will be shown.

![image](https://user-images.githubusercontent.com/37562094/67919055-375b8180-fb75-11e9-938c-7911d6a5eff6.png)


## Feature

* Longitude
* Latitude
* Magnitude
* Focal Depth
* Year

## Future Work

* A sliding timeline to select the year.
* Maps can be zoomed in or out



