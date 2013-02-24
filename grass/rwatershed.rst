R.WATERSHED - WATERSHED BASIN ANALYSIS PROGRAM.
===============================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Locations of real depressions[Raster]``:
- ``Amount of overland flow per cell[Raster]``:
- ``Percent of disturbed land, for USLE[Raster]``:
- ``Terrain blocking overland surface flow, for USLE[Raster]``:
- ``Minimum size of exterior watershed basin[Number]``:
- ``Maximum length of surface flow, for USLE[Number]``:
- ``Allow only horizontal and vertical flow of water[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Number of cells that drain through each cell[Raster]``:
- ``Drainage direction[Raster]``:
- ``Unique label for each watershed basin[Raster]``:
- ``Stream segments[Raster]``:
- ``Half-basins output layer[Raster]``:
- ``Visual display output layer[Raster]``:
- ``Slope length and steepness (LS) factor for USLE[Raster]``:
- ``Slope steepness (S) factor for USLE[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.watershed', elevation, depression, flow, disturbed.land, blocking, threshold, max.slope.length, -4, grass_region_parameter, grass_region_cellsize_parameter, accumulation, drainage, basin, stream, half.basin, visual, length.slope, slope.steepness)
