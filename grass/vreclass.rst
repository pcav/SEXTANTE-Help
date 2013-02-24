V.RECLASS - CHANGES VECTOR CATEGORY VALUES FOR AN EXISTING VECTOR MAP ACCORDING TO RESULTS OF SQL QUERIES OR A VALUE IN ATTRIBUTE TABLE COLUMN.
===============================================================================================================================================

Description
-----------

Parameters
----------

- ``Input layer[Vector]``:
- ``Feature type[String]``:
- ``The name of the column whose values are to be used as new categories[TableField]``:
- ``Reclass rule file[File]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Reclassified layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.reclass', input, type, column, rules, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
