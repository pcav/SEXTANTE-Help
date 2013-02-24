R.REPORT - REPORTS STATISTICS FOR RASTER LAYERS.
================================================

Description
-----------

Parameters
----------

- ``Raster layer(s) to report on[MultipleInput]``:
- ``Units[Selection]``:
- ``Character representing no data cell value[String]``:
- ``Number of fp subranges to collect stats from[Number]``:
- ``Suppress page headers[Boolean]``:
- ``Use formfeeds between pages[Boolean]``:
- ``Scientific format[Boolean]``:
- ``Filter out all no data cells[Boolean]``:
- ``Filter out cells where all layers have no data[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output report file[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.report', map, units, null, nsteps, -h, -f, -e, -n, -n, grass_region_parameter, output)

	Available options for selection parameters:

	units(Units)
		0 - mi
		1 - me
		2 - k
		3 - a
		4 - h
		5 - c
		6 - p
