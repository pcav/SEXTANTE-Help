R.TOPIDX - CREATES TOPOGRAPHIC INDEX LAYER FROM ELEVATION RASTER LAYER
======================================================================

Description
-----------

Parameters
----------

- ``Input elevation layer[Raster]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``output[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.topidx', input, grass_region_parameter, grass_region_cellsize_parameter, output topographic index layer)
