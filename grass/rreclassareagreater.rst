R.RECLASS.AREA.GREATER - RECLASSIFIES A RASTER LAYER, SELECTING AREAS LARGER THAN A USER SPECIFIED SIZE
=======================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Area threshold [hectares][Number]``:
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

	sextante.runalg('grass:r.reclass.area.greater', input, greater, grass_region_parameter, grass_region_cellsize_parameter, output)
