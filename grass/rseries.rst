R.SERIES - MAKES EACH OUTPUT CELL VALUE A FUNCTION OF THE VALUES ASSIGNED TO THE CORRESPONDING CELLS IN THE INPUT RASTER LAYERS.
================================================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer(s)[MultipleInput]``:
- ``Propagate NULLs[Boolean]``:
- ``Aggregate operation[Selection]``:
- ``Ignore values outside this range (lo,hi)[String]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Ouptut raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.series', input, -n, method, range, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	method(Aggregate operation)
		0 - average
		1 - count
		2 - median
		3 - mode
		4 - minimum
		5 - min_raster
		6 - maximum
		7 - max_raster
		8 - stddev
		9 - range
		10 - sum
		11 - variance
		12 - diversity
		13 - slope
		14 - offset
		15 - detcoeff
		16 - quart1
		17 - quart3
		18 - perc90
		19 - skewness
		20 - kurtosis
