V.UNIVAR - CALCULATES UNIVARIATE STATISTICS FOR ATTRIBUTE. VARIANCE AND STANDARD DEVIATION IS CALCULATED ONLY FOR POINTS IF SPECIFIED.
======================================================================================================================================

Description
-----------

Parameters
----------

- ``Name of input vector map[Vector]``:
- ``Feature type[String]``:
- ``Column name[TableField]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Percentile to calculate[String]``:
- ``Print the stats in shell script style[Boolean]``:
- ``Calculate extended statistics[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Statistics[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.univar', map, type, column, where, percentile, -g, -e, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, html)
