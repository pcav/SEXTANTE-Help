R.RESAMPLE - GRASS RASTER MAP LAYER DATA RESAMPLING CAPABILITY USING NEAREST NEIGHBORS.
=======================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer [Raster]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.resample', input, grass_region_parameter, grass_region_cellsize_parameter, output)
