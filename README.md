# Visualizing Palisades and Eaton Fire Scars Through True and False Color Imagery



<p align="center">
  <img src="https://images.foxweather.com/static.foxweather.com/www.foxweather.com/content/uploads/2025/01/668/376/8fce55a2-gettyimages-2192872847-scaled.jpg?ve=1&tl=1" alt="Palisades Fire as seen from Downtown Los Angeles" width="600">
  <br>
  <a href="https://www.foxweather.com/extreme-weather/los-angeles-fire-department-palisades-eaton-california-wildfires">Image source: FOX Weather</a>
</p>



## The Purpose of this Repository
This notebook explores how satellite imagery can be used to visualize the impacts of the January 2025 Eaton and Palisades Fires in Los Angeles County. Using Landsat 8 surface reflectance data and fire perimeter data, it creates true color and false color images and maps the burn scars alongside the official fire boundaries.


## File Structure 
```
eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-MATHEWS.ipynb
│--  .gitignore
```



## Highlights of the Analysis
- Exploring and wrangling raster data stored in a .nc file using `xarray` and `rioxarray` 
- Restoring missing information in a goespatial dataset
- Reprojecting vector data to match the raster's CRS 
- Handling outliers and missing values that restricts plotting
- Creating true color and false color images
- Combining raster and vector data to map fire scars and explain how false color imagery highlights burned areas more effectively


## Results




## About the Data
This analysis uses two datasets. The first is fire perimeter data for the Eaton and Palisades Fires from CAL FIRE’s Historical Fire Perimeter Dataset, downloaded as two individual shapefiles (one per fire). The second is a simplified collection of Landsat 8 Collection 2 Level-2 atmospherically corrected surface reflectance bands (red, green, blue, near-infrared, and shortwave infrared) collected on February 23, 2025. This data was retrieved from the Microsoft Planetary Computer, clipped to the area surrounding the fire perimeters. It is intended for visualization and educational purposes only.



## References
