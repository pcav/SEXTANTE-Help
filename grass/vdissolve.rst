V.DISSOLVE - DISSOLVES BOUNDARIES BETWEEN ADJACENT AREAS SHARING A COMMON CATEGORY NUMBER OR ATTRIBUTE.
=======================================================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Name of column used to dissolve common boundaries[TableField]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Dissolved layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.dissolve', input, column, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
