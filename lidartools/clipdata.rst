CLIP DATA
=========

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Extent[Extent]``:
- ``Shape[Selection]``:
- ``Additional modifiers[String]``:

Outputs
-------

- ``Output clipped las file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:clipdata', input, extent, shape, advanced_modifiers, output)

	Available options for selection parameters:

	shape(Shape)
		0 - Rectangle
		1 - Circle
