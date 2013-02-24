R.GROW.DISTANCE - GENERATES A RASTER LAYER OF DISTANCE TO FEATURES IN INPUT LAYER.
==================================================================================

Description
-----------

Parameters
----------

- ``Input input raster layer[Raster]``:
- ``Metric[Selection]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Distance layer[Raster]``:
- ``Output value[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.grow.distance', input, metric, grass_region_parameter, grass_region_cellsize_parameter, distance, value)

	Available options for selection parameters:

	metric(Metric)
		0 - euclidean
		1 - squared
		2 - maximum
		3 - manhattan
