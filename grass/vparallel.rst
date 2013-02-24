V.PARALLEL - CREATES PARALLEL LINE TO INPUT VECTOR LINES.
=========================================================

Description
-----------

Parameters
----------

- ``Input lines[Vector]``:
- ``Offset along major axis in map units[Number]``:
- ``Offset along minor axis in map units[Number]``:
- ``Angle of major axis in degrees[Number]``:
- ``Side[Selection]``:
- ``Tolerance of arc polylines in map units[Number]``:
- ``Make outside corners round[Boolean]``:
- ``Create buffer-like parallel lines[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Layer with parallel lines[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.parallel', input, distance, minordistance, angle, side, tolerance, -r, -b, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	side(Side)
		0 - left
		1 - right
		2 - both
