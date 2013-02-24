V.EXTRACT - SELECTS VECTOR OBJECTS FROM A VECTOR LAYER A NEW LAYER CONTAINING ONLY THE SELECTED OBJECTS.
========================================================================================================

Description
-----------

Parameters
----------

- ``Vector layer[Vector]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Dissolve common boundaries[Boolean]``:
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

	sextante.runalg('grass:v.extract', input, where, -d, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
