IMAGE CONVERSION
================

Description
-----------

Parameters
----------

- ``Input image[Raster]``:
- ``Rescale type[Selection]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:imageconversion', -in, -type, -ram, -out)

	Available options for selection parameters:

	-type(Rescale type)
		0 - none
		1 - linear
		2 - log2
