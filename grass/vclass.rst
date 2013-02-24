V.CLASS - CLASSIFIES ATTRIBUTE DATA, E.G. FOR THEMATIC MAPPING.
===============================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Column name or expression[TableField]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Algorithm to use for classification[Selection]``:
- ``Number of classes to define[Number]``:
- ``Print only class breaks (without min and max)[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Classification[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.class', map, column, where, algorithm, nbclasses, -g, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, html)

	Available options for selection parameters:

	algorithm(Algorithm to use for classification)
		0 - int
		1 - std
		2 - qua
		3 - equ
		4 - dis
