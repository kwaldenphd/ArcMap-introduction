# Introduction to ArcMap and GIS 

This tutorial was written by <a href="https://www.grinnell.edu/users/waldenka">Katherine Walden</a> (Digital Liberal Arts Specialist, Grinnell College). The tutorial framework was created by Sarah Purcell (L.F. Parker Professor of History, Grinnell College). Tutorial instructions were co-authored by Martin Toney, a student workers in the Grinnell College’s <a href="http://dasil.sites.grinnell.edu/">Data Analysis and Social Inquiry Lab</a> and Sophia Gates Stern, student mentor for this class.

This tutorial was reviewed by <a href="https://www.grinnell.edu/users/donovang">Gina Donovan</a> (Instructional Technologist) at Grinnell College, and edited by Lauren Frankel, a student worker in Grinnell College’s <a href="http://dasil.sites.grinnell.edu/">Data Analysis and Social Inquiry Lab</a>.

This tutorial uses <a href="http://www.cameronblevins.org/postal-data/">data generated by Cameron Blevins</a> and posted on his personal site.

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
ArcGIS Tutorial is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

<hr />

<em><a href="https://www.arcgis.com/index.html">ArcGIS</a> is an industry-standard tool developed by geographers in the 1970s. As digital historians have pursued more complex and large-scale spatial analysis projects, ArcGIS is a tool frequently used to visualize and analyze spatial data. The ArcGIS Online platform (not covered in this tutorial but featured in many digital mapping projects) allows data analyzed and visualized in ArcGIS to be interactive and publicly-accessible. We will continue working with <a href="http://www.cameronblevins.org/postal-data/">Cameron Blevins's postal data</a> for this tutorial.</em>

<hr />

## Data

1-Download the <strong>Data</strong> folder from this GitHub repo.

2-This folder will contain a <strong>folder </strong>(cb_2016_us_state_5m) and <strong>CSV file</strong> (1871_PostmasterSalary_Data.csv)

3-Copy both files to the Desktop.

4-Open the cb_2016_us_state_5m folder.

5- Explore the file extensions, and open the CSV file (1871_PostmasterSalary_Data.csv) to review the structure of the postal data.

<blockquote>A note on file types:

ArcGIS draws data on a map using shape files (.shp). A Shapefile is actually comprised of a package of individual files, but ArcGIS reads all of  those files together as a Shapefile. Once in ArcGIS, Shapefiles become part of layers. ArcGIS can read other file types (CSV, GeoJson, KML), but the program needs to turn that data into a Shapefile in order to save, analyze, and export it.</blockquote>

## Starting ArcMap and Importing Data:

6-To open ArcMap, go to <strong>Start</strong>, then type "ArcMap" into the search bar. Click on the globe icon that pops up to start the program.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_1.PNG?raw=true"><img class="aligncenter size-full wp-image-518" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_1.PNG?raw=true" alt="" width="799" height="519" /></a></p>

7-Click on the <strong>Blank Map</strong> icon, and the program will open a blank ArcGIS map project. Save this project as "GIS_Tutorial" or another descriptive name of your choosing.

## Importing Shapefiles into ArcMap:

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_2.PNG?raw=true"><img class="aligncenter size-full wp-image-519" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_1.PNG?raw=true" alt="" /></a></p>

8-Click on the <strong>Catalog</strong> button on the right-hand side of the window to open <strong>ArcCatalog</strong>, ArcMap's program for connecting to files on your computer. ArcCatalogue can be run independently or within ArcMap, and locates files on your computer using folder connections.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_4.PNG?raw=true"><img class="aligncenter size-full wp-image-521" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_4.PNG?raw=true" alt="" width="304" height="479" /></a></p>

9-Click on the "Connect to Folder" button near the top of the Catalogue window. Navigate to the <strong>Desktop</strong> where your <strong>cb_2016_us_state_5m folder</strong> is located. Click on the folder and select <strong>OK</strong>. The folder will now appear in your catalogue window.

10-Click on the <strong>"+"</strong> symbol next to the folder, which will expand to show the files included in the folder.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_5.PNG?raw=true"><img class="aligncenter size-large wp-image-522" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_5.PNG?raw=true" alt="" width="676" height="356" /></a></p>

11-Locate the <strong>cb_2016_us_state_5m.shp</strong> file, then drag it into the large blank canvas in the middle of the main window. You should now see a U.S. state map drawn in the main canvas.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_2.PNG?raw=true"><img class="aligncenter size-full wp-image-565" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_2.PNG?raw=true" alt="" width="285" height="58" /></a></p>

12-Save the project by clicking the <strong>floppy disc icon</strong> in the top-left.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_6.PNG?raw=true"><img class="aligncenter size-full wp-image-523" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_6.PNG?raw=true" alt="" width="457" height="219" /></a></p>

13-Go back to the <strong>Catalog</strong> window, and add another folder connection to your <strong>Desktop</strong>, where the <strong>1871_PostmasterSalary_Data.csv</strong> file is located. Drag the CSV file to the left-hand side of the ArcMap window, under <strong>Table of Contents</strong> and <strong>Layers</strong>.

14-Save the map project.

&nbsp;
<blockquote>Another note on file types:

ArcGIS loads shapefiles and uses them to create layers. Within the Table of Contents, you will see the shapefiles and data that have been added to the project.</blockquote>

## Adding data points to the map:

15-Right now, the <strong>cb_2016 shape file</strong> is drawing shape outlines, but the <strong>1871_PostmasterSalary_Data CSV file</strong> does not have any spatial data to display.

16-Right click on the CSV file in the <strong>Table of Contents</strong> and select <strong>Display XY Data... </strong>from the dropdown menu.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_7.PNG?raw=true"><img class="aligncenter size-full wp-image-524" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_7.PNG?raw=true" alt="" width="357" height="564" /></a></p>

17-On the pop-up screen, double check that <strong>Longitude</strong> is selected in the X field and <strong>Latitude</strong> is selected in the Y field. No value is needed for the Z field.

18-Click <strong>OK</strong>, and click <strong>OK</strong> again after the Object-ID Field error pops up.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_8.PNG?raw=true"><img class="aligncenter size-full wp-image-525" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_8.PNG?raw=true" alt="" width="907" height="649" /></a></p>

19-The points from the CSV file have been added to your map as an <strong>Events layer</strong> (see image above) but needed to be saved as a Shapefile.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_9.PNG?raw=true"><img class="aligncenter size-full wp-image-526" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_9.PNG?raw=true" alt="" width="399" height="330" /></a></p>

20-Right click on the <strong>Events layer</strong> and select <strong>Data-&gt;Export Data.</strong> A dialogue box will pop  up prompting you to choose the export features and coordinate system.

21-Leave the <strong>Export</strong> as the default and select <strong>"the data frame"</strong> for the coordinate system.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_10.PNG?raw=true"><img class="aligncenter size-full wp-image-527" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_10.PNG?raw=true" alt="" width="857" height="644" /></a></p>

22-Rename the output feature class to <strong>Postal_GIS.shp</strong> and click <strong>OK.</strong> A window will pop up asking if you want to display the exported data as a layer--click <strong>Yes.</strong> A <strong>Postal_GIS layer</strong> should now appear in your <strong>Table of Contents.</strong>

23-The checkboxes next to layer names allow you to decide which layers are drawn on your map. Right click on the <strong>Postal_GIS.csv Events</strong> layer and the <strong>Postal_GIS.csv file</strong> and select remove to remove these layers from your project.

24-Save the project.

### A note on navigating ArcMap:

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_11.PNG?raw=true"><img class="aligncenter size-full wp-image-528" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_11.PNG?raw=true" alt="" width="618" height="56" /></a></p>

By this point, you may want to explore your map in more detail. The "+" symbol on the main page allows you to zoom in, and the "-" icon is a zoom-out option. The "hand" lets you drag the map around, and the i icon lets you see the dated represented by a specific point.

## Customizing your display:

25-Right now, the geographic information is being drawn on the map according to ArcMap's default settings. The <strong>Symbology</strong> property allows us to customize how data displays on the map.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_12.PNG?raw=true"><img class="aligncenter size-full wp-image-529" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_12.PNG?raw=true" alt="" width="672" height="563" /></a></p>

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_12.PNG?raw=true"><img class="aligncenter size-full wp-image-530" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_12.PNG?raw=true" alt="" width="672" height="559" /></a></p>

26-Right click on the <strong>Postal_GIS layer</strong> and select <strong>Properties</strong> from the dropdown menu. Click on the <strong>Symbology</strong> tab, and select <strong>Quantities-&gt;Graduated</strong> colors under the <strong>Show</strong> menu on the left-hand side of the <strong>Symbology</strong> window.

27-<strong>Categories</strong> would recolor map points by a specific data field, and <strong>Quantities</strong> colors map points by calculating quantities in the data.

28-In the <strong>Value</strong> field, select <strong>PM_Salary</strong> from the dropdown. ArcMap will use the values in the PM_Salary field to determine numeric ranges.

29-The <strong>Color Ramp</strong> dropdown gives you additional options for coloring your data points.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_14.PNG?raw=true"><img class="aligncenter size-full wp-image-531" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_14.PNG?raw=true" alt="" width="629" height="486" /></a></p>

By default, ArcMap calculates the ranges using Jenks or Natural Breaks. Click the Classify icon to choose other ways of calculating these intervals.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_15.PNG?raw=true"><img class="aligncenter size-full wp-image-532" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_15.PNG?raw=true" alt="" width="888" height="646" /></a></p>

30-Leave the other options at their defaults and click <strong>OK</strong>. Notice map points have changed color based on ranges in the postmaster's salary. The <strong>Table of Contents</strong> now includes a legend under the <strong>Postal_GIS layer</strong> that specifies the salary range for each color.

31-Save your project.

### Additional display options:

<ul>
 	<li>We are using the cb_shape file to draw the U.S. map with state boundaries for our data points. We could also use a basemap in ArcMap to display this background. In the <strong>Table of Contents</strong>, uncheck the cb_shape file. Click on the <strong>Add Data</strong> icon and select <strong>Add a Basemap</strong> to see ArcMap's default basemap options. Select a basemap and compare your experience navigating the two different maps. What would be the advantages and disadvantages of using one of ArcMap's basemaps versus using a shapefile to draw the background?</li>
 	<li>You were instructed to color your points based on postmaster salary ranges. What happens when you go back to <strong>Properties-&gt;Symbology</strong> and select a different value (under <strong>Fields</strong>) or select a different option under <strong>Show</strong>? What aspects of the data are emphasized (or become unclear) based on how you display points on the map?</li>
</ul>

## Using the ArcToolbox:

In addition to visualizing map points, ArcMap includes a wide range of analysis tools, located in the <strong>ArcToolbox</strong>. We will use a spatial analysis tool to look at the density of points in our Postal_GIS shape file, calculated as a magnitude per unit area of points. The neighborhood radius defines the area around each cell from which the magnitude will be calculated.

<blockquote>Even though map layers are based on shapefiles, those files can contain very different types of spatial data. The cb_shapefile that includes state and county boundaries is showing polygon data, while the Postal_GIS layer is showing point data. Like we see with the postal data, combining points and polygons can be useful for analysis. ArcMap just requires each layer or shapefile to represent one type of spatial data. You could have points and polygons within a map project--just not in the same shapefile or layer.</blockquote>

ArcMap also gives you the option of displaying <strong>raster data</strong>. <strong>Raster layers</strong> consist of data that varies continuously or gradually. Data about elevation, geography, weather trends, and similar phenomena are mapped using raster data and raster lays. In the next section of the tutorial, we will use a spatial analysis tool to create a raster layer based on the Postal_GIS points layer.

## Mapping Clusters:

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_2.PNG?raw=true"><img class="aligncenter size-full wp-image-519" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_2.PNG?raw=true" alt="" width="147" height="23" /></a></p>

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_16.PNG?raw=true"><img class="aligncenter size-full wp-image-534" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_16.PNG?raw=true" alt="" width="301" height="600" /></a></p>

32-Select the <strong>ArcToolbox</strong>, and click the dropdown for <strong>Spatial Analyst</strong>. Click on <strong>Point Density</strong>.

33-If the tool doesn't open, click on the Customize dropdown at the main ArcMap menu, select <strong>extensions</strong>, and be sure <strong>spatial analyst</strong> is checked.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_17.PNG?raw=true"><img class="aligncenter size-full wp-image-535" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_17.PNG?raw=true" alt="" width="588" height="415" /></a></p>

34-Select <strong>Postal_GIS</strong> for <strong>Input point features</strong>. Leave <strong>Population field</strong> as <strong>NONE</strong> for now. Change the name of the output layer to <strong>Postal_Den</strong> and leave the other options as defaults. Click <strong>OK</strong>.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_19.PNG?raw=true"><img class="aligncenter size-large wp-image-537" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_19.PNG?raw=true" alt="" width="676" height="535" /></a></p>

35-A new layer should appear in your table of contents. If the new layer is covered by other layers, we need to change the drawing order of layers to make the density layer visible.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_20.PNG?raw=true"><img class="aligncenter size-full wp-image-538" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_20.PNG?raw=true" alt="" width="151" height="47" /></a></p>

36-Click on the <strong>Drawing Order View</strong> icon in the <strong>Table of Contents</strong> to select the drawing order view.

37-Click and drag the <strong>Postal_Den</strong> layer to be between the <strong>cb_shapefile</strong> and <strong>Postal_GIS</strong> layer. You should see a colored square between the U.S. map layer and the points.

38-The reason we're seeing the large solid-color square is because the lowest range of density values in the layer is still displaying with a solid color, rather than a lighter shade or more transparent color option.

39-Right click on the <strong>Postal_Den</strong> layer and select <strong>Properties</strong> from the dropdown.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_22.PNG?raw=true"><img class="aligncenter size-full wp-image-540" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_22.PNG?raw=true" alt="" width="654" height="502" /></a></p>

40-Select <strong>Symbology</strong> and see the numeric ranges assigned to each color under <strong>Symbol</strong>.

41-Double click on the color box for the first range (0.00-9.88) and select <strong>No color.</strong> This option makes the first range transparent so the smaller values are not distorting the map layers.

<a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_23.PNG?raw=true"><img class="aligncenter size-large wp-image-541" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_23.PNG?raw=true" alt="" width="676" height="527" /></a>
42-Zoom in on a particular high-density cluster to see the individual points that contributed to the density analysis. This first density calculation was based on the number of map points.

43-We will add another raster layer by calculating where the point density for higher-paying postmaster positions.

44-Reopen the point density tool.

45-Use the same <strong>Postal_GIS</strong> layer, but select <strong>PM_Salary</strong> (rather than population field) from the dropdown.

46-Rename the output to <strong>Salary_Den.</strong>

47-Customize the layer's display like we did with the original density calculation. You can also select a different color ramp under <strong>Properties-&gt;Symbology.</strong>

## Using ArcToolbox to calculate spatial statistics:

In addition to creating new spatial visualizations of our data, ArcMap can also calculate spatial statistics for our data. Spatial statistics can be used to predict or highlight causal relationship between the distribution of points and their attributes. For example, spatial statistics indicate a correlation between the location of houses and the incomes of home residents. We will use the spatial statistic tools to see if there is a significant spatial relationship for postmaster salaries.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_24.PNG?raw=true"><img class="aligncenter size-full wp-image-542" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_24.PNG?raw=true" alt="" width="428" height="597" /></a></p>

48-Reopen <strong>ArcToolbox</strong> and select <strong>Analyzing Patterns</strong> within <strong>Spatial Statistics</strong>. Select <strong>Spatial Autocorrelation (Morans I).</strong>

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_25.PNG?raw=true"><img class="aligncenter size-full wp-image-543" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_25.PNG?raw=true" alt="" width="592" height="416" /></a></p>

49-For <strong>Input Feature Class</strong>, select <strong>Postal_GIS</strong> layer from the dropdown.

50-For <strong>Input Field</strong> select <strong>PM_Salary</strong>.

51-Check the <strong>Generate Report</strong> button.

52-Next is the <strong>Conceptualization of Spatial Relationships</strong> dropdown, which gives us several options to define how the relationship degrades with distance--how the spatial correlation between two points becomes weaker as the distance between them increases. Select <strong>Inverse Distance</strong>, which works well for point data since the relationship degrades as (1/distance).

53-Leave the other fields as defaults and select <strong>OK</strong>.

54-You will see a <strong>blue rectangular pop-up</strong> in the bottom right corner of the screen. A <strong>checkmark</strong> means the analysis was completed successfully, and a <strong>caution sign</strong> means errors occurred during the analysis.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_26.PNG?raw=true"><img class="aligncenter size-large wp-image-544" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_26.PNG?raw=true" alt="" width="676" height="382" /></a></p>

55-To open the <strong>analysis report</strong>, click on the <strong>Geoprocessing-&gt;Results </strong>to see the analysis results.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_27.PNG?raw=true"><img class="aligncenter size-large wp-image-545" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_27.PNG?raw=true" alt="" width="676" height="489" /></a></p>

56-Click on the <strong>Report File html</strong> file, which will open in a browser window. What does the report say about the randomness of the data? To what degree is it clustered, random, or dispersed? What could those trends say about the distribution of postmaster salaries across western states?

57-Rerun the <strong>Spatial Autocorrelation</strong> analysis, using <strong>Fixed Distance Band</strong> instead of <strong>Inverse Distance</strong> for the conceptualization of the spatial relationship. The <strong>Fixed Distance Band</strong> uses a fixed distance and calculates a correlation value of 0 to 1 based on that fixed distance.

58-Open this analysis's <strong>Report File</strong> to see how the results changed based on how ArcMap conceptualized the spatial relationship. What changed in the analysis results? How would you describe the data's spatial correlation?

<hr />

## Exporting Your Map as an Image File
For this tutorial, you'll export the map you created as an image, without adding titles, legends, or other map elements that would be necessary for a user to interact with or "read" your map.

ArcMap gives you the option to add scale bars, images, and legends to your map using the Page Layout functionality. <a href="http://desktop.arcgis.com/en/arcmap/latest/map/page-layouts/a-quick-tour-of-page-layouts.htm">Click here</a> to learn more about Page Layouts.

<p align="center"><a href="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_29.PNG?raw=true"><img class="aligncenter size-full wp-image-638" src="https://github.com/kwaldenphd/ArcMap-introduction/blob/master/screenshots/Capture_29.PNG?raw=true" alt="" width="564" height="722" /></a></p>

59-Click <strong>File-Export Map</strong>, and select TIFF or JPG under <strong>Save as type</strong>. Change the resolution to 600 dpi (dots per inch) to export an image with archive-quality resolution.

60-Save the file to your Desktop as Postal_Tutorial or another descriptive name.

&nbsp;

<hr />

# Reflection questions: 

<ul>
 	<li><em>How is using a tool like ArcGIS for spatial analysis different than Carto or Google Maps?</em></li>
 	<li><em>What features or aspects of the data were you able to analyze and visualize in ArcGIS that you hadn't thought about before?</em></li>
 	<li><em>Drawing on your own historical interests, what types of data or data sources could you analyze and visualize using ArcGIS?</em></li>
 	<li><em>What are the limitations or challenges of a tool like ArcGIS for historical spatial analysis?</em></li>
 	<li><em>ArcGIS can do much more than we are exploring here; it is a very complex tool.  How does its complexity help or hurt your ability to use this tool to ask and answer historical questions?</em></li>
</ul>
