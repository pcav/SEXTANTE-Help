V.SEGMENT - CREATES POINTS/SEGMENTS FROM INPUT VECTOR LINES AND POSITIONS.
==========================================================================

Description
-----------

Parameters
----------

- ``Input lines layer[Vector]``:
- ``File containing segment rules[File]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output vector layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.segment', input, file, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
