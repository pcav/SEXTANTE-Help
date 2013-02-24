V.NORMAL - TESTS FOR NORMALITY FOR POINTS.
==========================================

Description
-----------

Parameters
----------

- ``point vector defining sample points[Vector]``:
- ``Lists of tests (1-15): e.g. 1,3-8,13[String]``:
- ``Attribute column[TableField]``:
- ``Use only points in current region[Boolean]``:
- ``lognormal[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.normal', map, tests, column, -r, -l, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, html)
