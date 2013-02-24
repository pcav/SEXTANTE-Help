R.BUFFER - CREATES A RASTER MAP LAYER SHOWING BUFFER ZONES SURROUNDING CELLS THAT CONTAIN NON-NULL CATEGORY VALUES.
===================================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Distance zone(s) (e.g. 100,200,300)[String]``:
- ``Units of distance[Selection]``:
- ``Ignore zero (0) data cells instead of NULL cells[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Buffer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.buffer', input, distances, units, -z, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	units(Units of distance)
		0 - meters
		1 - kilometers
		2 - feet
		3 - miles
		4 - nautmiles
