GEOMETRIC FIGURES
=================

Description
-----------

Parameters
----------

- ``Cell Count[Number]``:
- ``Cell Size[Number]``:
- ``Figure[Selection]``:
- ``Direction of Plane [Degree][Number]``:

Outputs
-------

- ``Result[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:geometricfigures', cell_count, cell_size, figure, plane, result)

	Available options for selection parameters:

	figure(Figure)
		0 - [0] Cone (up)
		1 - [1] Cone (down)
		2 - [2] Plane
