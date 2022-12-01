# **StaGeoMod2022 week 12 -[Spatial Interpolation]**

## Objectives of this week.

1. Load, create, manipulate, and save `Spatial*` and `Raster*` object types in `R`.
2. Perform Non-Geostatistical interpolations in `R`.
3. Perform Geostatistical interpolations in `R`.


## Some basics on interpolation

Almost any variable of interest measured in the field has spatial autocorrelation (i.e., systematic spatial variation in a variable). That can be a problem in statistical tests as it violates a core assumption for most (if not all) statistical tests - independence of observations. However,  spatial autocorrelation is a handy feature when the goal is to predict values at locations where no measurements have been made. You can generally safely assume that values at nearby areas will be similar (positively spatially autocorrelated). Several spatial interpolation techniques are geostatistical (Kriging, co-kriging), and others focus on using the location of the network of observations and/or distances between these.


