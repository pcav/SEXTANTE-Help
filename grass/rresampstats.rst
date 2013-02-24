R.RESAMP.STATS - RESAMPLES RASTER LAYERS TO A COARSER GRID USING AGGREGATION.
=============================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Aggregation method[Selection]``:
- ``Propagate NULLs[Boolean]``:
- ``Weight according to area (slower)[Boolean]``:
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

	sextante.runalg('grass:r.resamp.stats', input, method, -n, -w, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	method(Aggregation method)
		0 - average
		1 - median
		2 - mode
		3 - minimum
		4 - maximum
		5 - quart1
		6 - quart3
		7 - perc90
		8 - sum
		9 - variance
		10 - stddev
