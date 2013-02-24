V.REPORT - REPORTS GEOMETRY STATISTICS FOR VECTORS.
===================================================

Description
-----------

Parameters
----------

- ``Input layer[Vector]``:
- ``Value to calculate[Selection]``:
- ``units[Selection]``:
- ``Reverse sort the result[Boolean]``:
- ``Sort the result[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Report HTML file[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.report', map, option, units, -r, -s, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, html)

	Available options for selection parameters:

	option(Value to calculate)
		0 - area
		1 - length
		2 - coor

	units(units)
		0 - miles
		1 - feet
		2 - meters
		3 - kilometers
		4 - acres
		5 - hectares
		6 - percent
