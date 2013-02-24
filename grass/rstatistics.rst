R.STATISTICS - CALCULATES CATEGORY OR OBJECT ORIENTED STATISTICS.
=================================================================

Description
-----------

Parameters
----------

- ``Base raster layer[Raster]``:
- ``Cover raster layer[Raster]``:
- ``method[Selection]``:
- ``Cover values extracted from the category labels of the cover map[Boolean]``:
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

	sextante.runalg('grass:r.statistics', base, cover, method, -c, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	method(method)
		0 - diversity
		1 - average
		2 - mode
		3 - median
		4 - avedev
		5 - stddev
		6 - variance
		7 - skewness
		8 - kurtosis
		9 - min
		10 - max
		11 - sum
