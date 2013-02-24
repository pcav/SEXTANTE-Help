SELECT BY ATTRIBUTE
===================

Description
-----------

Parameters
----------

- ``Input Layer[Vector]``:
- ``Selection attribute[TableField]``:
- ``Comparison[Selection]``:
- ``Value[String]``:

Outputs
-------

- ``Output[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('qgis:selectbyattribute', layername, attribute, comparison, comparisonvalue)

	Available options for selection parameters:

	comparison(Comparison)
		0 - ==
		1 - !=
		2 - >
		3 - >=
		4 - <
		5 - <=
		6 - begins with
		7 - contains
