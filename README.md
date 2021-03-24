# Raster intersect
Intersect two raster, return the array of intersected area of two raster 

## Example command to run.

raster1_gdal = gdal.Open(raster1_path)

raster2_gdal = gdal.Open(raster2_path)


image1_isect_array, image2_isect_array, col, row, isect_bb = findRasterIntersect(raster1_gdal, raster2_gdal)


## Package

gdal

## Credit 
https://sciience.tumblr.com/post/101722591382/finding-the-georeferenced-intersection-between-two
