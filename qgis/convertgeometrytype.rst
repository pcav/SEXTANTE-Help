CONVERT GEOMETRY TYPE
=====================

Description
-----------

Parameters
----------

- ``Input layer[Vector]``:
- ``New Geometry Type[Selection]``:

Outputs
-------

- ``Output[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('qgis:convertgeometrytype', layername, newtype, savename)

	Available options for selection parameters:

	newtype(New Geometry Type)
		0 - Centroids
		1 - Nodes
		2 - Linestrings
		3 - Multilinestrings
		4 - Polygons
