# BTECH_EVALUATION_TASK
## Raster Tile Mosaicing

A raster mosaicing task focused on generating a cloudless mosaic image by seamlessly merging multiple georeferenced satellite raster tiles (GeoTIFFs). The code should efficiently combine overlapping tiles with consistent spatial resolution and coordinate reference systems, ensuring smooth transitions between scenes. The final output must be a clean, cloud-free mosaic, properly georeferenced and visualized using Python-based geospatial libraries. The complete workflow should be demonstrated in a Jupyter Notebook (Kaggle/Colab) using the provided sample raster tiles.

## Key Requirements

1. Design a Python-based workflow to merge multiple adjacent GeoTIFF raster tiles into a single cloudless mosaic.
2. Ensure proper handling of spatial reference, alignment, and NoData values.
3. Produce a seamless, georeferenced raster output suitable for visualization and analysis.
4. Demonstrate the complete process in a Jupyter Notebook (Kaggle/Colab) using sample data.

## Expected Output

The final deliverables should include:
1. Output Raster File – cloudless_mosaic.tif

   1.1. Single, georeferenced GeoTIFF mosaic of the input tiles
   
   1.2. Consistent spatial resolution and CRS
2. Code Notebook / Script (.ipynb/.py) – Contains your implementation and workflow
3. README File – Briefly explains:
   
   1.1. Libraries used

   1.2. Steps to run the code

   1.3. Summary of results

## Sub-Tasks For Evaluation

1. Read and Validate Tiles – Load multiple GeoTIFF rasters and verify projection, resolution, and spatial extent.
2. Reproject or Resample (if required) – Implement reprojection or resampling to ensure uniform spatial properties.
3. Mosaic Creation – Code the logic to merge all tiles into a single seamless raster using suitable geospatial libraries.
4. Overlap and NoData Handling – Implement a clear strategy to manage overlapping regions and missing data.
5. Color Consistency – Maintain uniform visual appearance across tiles to avoid visible tonal differences in the mosaic.
6. Output and Georeferencing Validation – Export the final mosaic as a properly georeferenced GeoTIFF and verifying spatial accuracy and metadata integrity of the output.
7. Visualization and Result Reporting – Present clear visual outputs of the cloudless mosaic and summarize key spatial properties, observations, and results.
