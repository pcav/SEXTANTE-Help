R.MEDIAN - FINDS THE MEDIAN OF VALUES IN A COVER LAYER WITHIN AREAS ASSIGNED THE SAME CATEGORY VALUE IN A USER-SPECIFIED BASE LAYER.
====================================================================================================================================

Description
-----------

Parameters
----------

- ``Base raster layer[Raster]``:
- ``Cover layer[Raster]``:
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

	sextante.runalg('grass:r.median', base, cover, grass_region_parameter, grass_region_cellsize_parameter, output)
