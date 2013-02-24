R.NEIGHBORS - MAKES EACH CELL CATEGORY VALUE A FUNCTION OF THE CATEGORY VALUES ASSIGNED TO THE CELLS AROUND IT
==============================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Neighborhood operation[Selection]``:
- ``Neighborhood size[Number]``:
- ``Use circular neighborhood[Boolean]``:
- ``Do not align output with the input[Boolean]``:
- ``File containing weights[File]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.neighbors', input, method, size, -c, -a, weight, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	method(Neighborhood operation)
		0 - average
		1 - median
		2 - mode
		3 - minimum
		4 - maximum
		5 - stddev
		6 - sum
		7 - variance
		8 - diversity
		9 - interspersion
