## PRIORITY MAPS



***
 <font color='green'>Spatial multicriteria analysis is an analysis technique that transforms and combines geographical data and value judgements to provide a systematic analytical approach  that can be used for decision making. Decision making can include identifying risk levels, uncertainty, developing prioritization maps. We can develop models based on various factors and weigh/rank those factors by providing scores/choices. We have used following datasets in our model: 

## Elevation:
We have used Shuttle Radar Topography Mission (SRTM) digital elevation data which provides elevation of 1 arc-second (approximately 30 m) in our model. We have used global data so that users can choose/select/filter the location of their interest and build the model. For more information about this dataset please visit SRTM Quick Guide.
 
 
 
## Bioclimatic variables:
We have used WorldClim V1 Bioclim datasets that are derived from the monthly temperature and rainfall in our model. This dataset can be used to study annual temperature and precipitation trends,  seasonality. We have used only two bioclimatic variables in our model(i):  bio 1: annual temperature in °C. Minimum temperature  is -290 and maximum temperature is 320 °C. (ii): Annual precipitation in mm. The lowest value is 0 and the highest is 11401 mm. 

 
 
## Land use land cover:
We have used global land cover data for 2020 at 10 m resolution based on Sentinel-1 and Sentinel-2 data. It has 11 land cover classes.
 

## Vegetation datasets:
We used The Terra MODIS Vegetation Continuous Fields (VCF) to derive a gradation of three surface cover components: percent tree cover, percent non-tree cover, and percent bare. These products are generated yearly, the VCF product is produced using monthly composites of Terra MODIS 250 and 500 meters Land Surface Reflectance data, including all seven bands, and Land Surface Temperature.
 


 

## Model development
We used only raster as the input layers in our models. We used both continuous and discrete (LULC) raster in our model. We resampled the input layers to match the resolution and cell size of all the input layers. Users can then reclassify the continuous raster either in ascending (increasing values/lowest to highest) or descending (highest to lowest) in their model based on the requirements of the projects. Then the model is built on weighted overlay sum concept. The sum of all the weights/scores should be equal to 100.  We provide scores based on varying levels of ‘importance’ or weights to the different input layers. 

  A quick video demonstrating the method to use this application has been uploaded. Please watch the video before using the application. You may also contact  the developer of this application at ritikaprasai3@gmail.com should you have any questions or recommendations/suggestion. We will work on adding more functionatilies based on user's feedback to this model. If you are using the web-based tool for your research please cite the tool using the given information</font>





- *Author full name: Ritika Prasai*
- *Release date: 19 April, 2022*
- *Application title: Prioritymaps.com*
- *Version: 1.0*
- *URL: https://www.prioritymaps.com/*

A publication is under review

<h1><font color='green'>Watch-video</font> </h1>

<p align="center">
<<iframe width="560" height="315" src="https://www.youtube.com/embed/iPLx_3WNGMw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>>
</p>
