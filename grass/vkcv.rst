V.KCV - RANDOMLY PARTITION POINTS INTO TEST/TRAIN SETS.
=======================================================

Description
-----------

Parameters
----------

- ``Input layer[Vector]``:
- ``Number of partitions[Number]``:
- ``Name for new column to which partition number is written[String]``:
- ``Use drand48()[Boolean]``:
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

	sextante.runalg('grass:v.kcv', input, k, column, -d, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
