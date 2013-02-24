R.THIN - THINS NON-ZERO CELLS THAT DENOTE LINEAR FEATURES IN A RASTER LAYER.
============================================================================

Description
-----------

Parameters
----------

- ``Input raster layer to thin[Raster]``:
- ``Maximal number of iterations[String]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output thinned raster[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.thin', input, iterations, grass_region_parameter, grass_region_cellsize_parameter, output)
