RASTERIZATION
=============

Description
-----------

Parameters
----------

- ``Input vector dataset[File]``:
- ``Input reference image[Raster]``:
- ``Output size x[Number]``:
- ``Output size y[Number]``:
- ``Output EPSG code[Number]``:
- ``Output Upper-left x[Number]``:
- ``Output Upper-left y[Number]``:
- ``Spacing (GSD) x[Number]``:
- ``Spacing (GSD) y[Number]``:
- ``Background value[Number]``:
- ``Rasterization mode[Selection]``:
- ``Foreground value[Number]``:
- ``The attribute field to burn[String]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Ouptut image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:rasterization', -in, -im, -szx, -szy, -epsg, -orx, -ory, -spx, -spy, -background, -mode, -mode.binary.foreground, -mode.attribute.field, -ram, -out)

	Available options for selection parameters:

	-mode(Rasterization mode)
		0 - binary
		1 - attribute
