R.SURF.RANDOM - PRODUCES A RASTER LAYER OF UNIFORM RANDOM DEVIATES WHOSE RANGE CAN BE EXPRESSED BY THE USER.
============================================================================================================

Description
-----------

Parameters
----------

- ``Minimum random value[Number]``:
- ``Maximum random value[Number]``:
- ``Create an integer raster layer[Boolean]``:
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

	sextante.runalg('grass:r.surf.random', min, max, -i, grass_region_parameter, grass_region_cellsize_parameter, output)
