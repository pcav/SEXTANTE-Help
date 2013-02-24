V.OVERLAY - OVERLAYS TWO VECTOR MAPS.
=====================================

Description
-----------

Parameters
----------

- ``Input layer (A)[Vector]``:
- ``Input layer (B)[Vector]``:
- ``Operator to use[Selection]``:
- ``Do not create attribute table[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Overlay[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.overlay', ainput, binput, operator, -t, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	operator(Operator to use)
		0 - and
		1 - or
		2 - not
		3 - xor
