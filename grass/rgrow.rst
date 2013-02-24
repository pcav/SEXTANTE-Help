R.GROW - GENERATES A RASTER LAYER WITH CONTIGUOUS AREAS GROWN BY ONE CELL.
==========================================================================

Description
-----------

Parameters
----------

- ``input raster layer[Raster]``:
- ``Radius of buffer in raster cells[Number]``:
- ``Metric[Selection]``:
- ``Value to write for input cells which are non-NULL (-1 => NULL)[Number]``:
- ``Value to write for "grown" cells[Number]``:
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

	sextante.runalg('grass:r.grow', input, radius, metric, old, new, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	metric(Metric)
		0 - euclidean
		1 - maximum
		2 - manhattan
