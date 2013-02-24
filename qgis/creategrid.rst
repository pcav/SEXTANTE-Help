CREATE GRID
===========

Description
-----------

Parameters
----------

- ``Horizontal spacing[Number]``:
- ``Vertical spacing[Number]``:
- ``Width[Number]``:
- ``Height[Number]``:
- ``Center X[Number]``:
- ``Center Y[Number]``:
- ``Grid type[Selection]``:

Outputs
-------

- ``Output[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('qgis:creategrid', hspacing, vspacing, width, height, centerx, centery, gridtype, savename)

	Available options for selection parameters:

	gridtype(Grid type)
		0 - Rectangle (line)
		1 - Rectangle (polygon)
		2 - Diamond (polygon)
		3 - Hexagon (polygon)
