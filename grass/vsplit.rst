V.SPLIT - SPLIT LINES TO SHORTER SEGMENTS.
==========================================

Description
-----------

Parameters
----------

- ``Input lines layer[Vector]``:
- ``Maximum segment length[Number]``:
- ``Maximum number of vertices in segment[Number]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.split', input, length, vertices, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
