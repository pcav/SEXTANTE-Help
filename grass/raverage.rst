R.AVERAGE - FINDS THE AVERAGE OF VALUES IN A COVER RASTER LAYER  WITHIN AREAS ASSIGNED THE SAME CATEGORY VALUE IN A USER-SPECIFIED BASE LAYER.
==============================================================================================================================================

Description
-----------

Parameters
----------

- ``Base raster layer[Raster]``:
- ``Cover raster layer[Raster]``:
- ``Cover values extracted from the category labels of the cover map[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Average values[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.average', base, cover, -c, grass_region_parameter, grass_region_cellsize_parameter, output)
