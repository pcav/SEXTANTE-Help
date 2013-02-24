CREATE GRATICULE
================

Description
-----------

Parameters
----------

- ``Extent[Vector]``:
- ``Output extent[Extent]``:
- ``Division Width[Number]``:
- ``Division Height[Number]``:
- ``Type[Selection]``:

Outputs
-------

- ``Graticule[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:creategraticule', extent, output_extent, distx, disty, type, graticule)

	Available options for selection parameters:

	type(Type)
		0 - [0] Lines
		1 - [1] Rectangles
