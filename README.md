# Analysis of Land Cover Classification in Santa Barbara
Using supervised classification to perform a landcover classification of 2020 Southern Santa Barbara County.

## Goals
- Train a decision tree classifier using spectral reflectance data
- Classify land cover types of Southern Santa Barbara County


## Visualizations
- This project produced a visualization of the landcover classifications in Southern Santa Barbara using `tmap`


## Skills Highlights
-   build decision tree using spectral reflectance data to classify landsat images
-   combining vector and raster data
-   resampling raster data
-   Visualize rasters using `tmap`



Contents/Structure:


    land-cover-classification
        │ README.md 
        │ Rmd/Proj files
        │ 
        └───data 
             | landsat-data
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B1.TIF
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B2.TIF
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B3.TIF
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B4.TIF
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B5.TIF
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B6.TIF
             |     | LT05_L2SP_042036_20070925_20200829_02_T1_SR_B7.TIF
             │  
             │ SB_county_south
             │     | shapefiles 
             │
             │ 
             │ trainingdata
                   | shapefiles
                   
### Data Access
All data to conduct this analysis is stored in the `data` folder.
- The landsat data is from [Landsat 5](https://www.usgs.gov/landsat-missions/landsat-5), and we used 1 scene from September 25, 2007. - bands: 1, 2, 3, 4, 5, 7 - Collection 2 surface reflectance product.
