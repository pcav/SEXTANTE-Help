V.OUT.POV - CONVERTS TO POV-RAY FORMAT, GRASS X,Y,Z -> POV-RAY X,Z,Y
====================================================================

Description
-----------

Parameters
----------

- ``Name of input vector map[Vector]``:
- ``Feature type[String]``:
- ``Modifier for z coordinates, this string is appended to each z coordinate[String]``:
- ``Object modifier (OBJECT_MODIFIER in POV-Ray documentation)[String]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.out.pov', input, type, zmod, objmod, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
