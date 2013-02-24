V.QCOUNT - INDICES FOR QUADRANT COUNTS OF SITES LISTS.
======================================================

Description
-----------

Parameters
----------

- ``Vector points layer[Vector]``:
- ``Number of quadrants[Number]``:
- ``Quadrat radius[Number]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output quadrant layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.qcount', input, n, r, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
