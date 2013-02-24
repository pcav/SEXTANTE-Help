V.HULL - PRODUCES A CONVEX HULL FOR A GIVEN VECTOR MAP.
=======================================================

Description
-----------

Parameters
----------

- ``Input layer[Vector]``:
- ``Use all vector points (do not limit to current region)[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Convex hull[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.hull', input, -a, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
