R.SURF.GAUSS - CREATES A RASTER LAYER OF GAUSSIAN DEVIATES.
===========================================================

Description
-----------

Parameters
----------

- ``Distribution mean[String]``:
- ``Standard deviation[String]``:
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

	sextante.runalg('grass:r.surf.gauss', mean, sigma, grass_region_parameter, grass_region_cellsize_parameter, output)
