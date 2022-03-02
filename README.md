# Raster_tools - zonal stats

Zonal stat extraction is an essential component of raster analysis to compose usable insights out of raster analysis. In ecology, or agriculture, efficient raster analysis procedures should be equipped with the bulk-batch processing capabilities to add more reasonable time components (generating time series).

This notebook iterates over the daily evapotranspiration dataset and extracts daily zonal statistics values based on Landcover type. Land Cover types are corn, soybean, alfalfa, wheat, grass, deciduous. For the statistical data display, web compatible, modern data visualization techniques will be used.

# condition based raster generation
This code will read values from 2 different raster images and create a new raster based on applied condtions
