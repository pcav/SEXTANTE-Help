R.RANDOM - CREATES A RASTER LAYER AND VECTOR POINT MAP CONTAINING RANDOMLY LOCATED POINTS.
==========================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Input cover raster layer[Raster]``:
- ``The number of points to allocate[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster layer[Raster]``:
- ``Output vector layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.random', input, cover, n, grass_region_parameter, grass_region_cellsize_parameter, raster_output, vector_output)
