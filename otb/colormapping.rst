COLOR MAPPING
=============

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Operation[Selection]``:
- ``Not Found Label[Number]``:
- ``Color mapping method[Selection]``:
- ``Look-up table file[File]``:
- ``Look-up tables[Selection]``:
- ``Mapping range lower value[Number]``:
- ``Mapping range higher value[Number]``:
- ``Background label[Number]``:
- ``Support Image[Raster]``:
- ``lower quantile[Number]``:
- ``upper quantile[Number]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:colormapping', -in, -ram, -op, -op.colortolabel.notfound, -method, -method.custom.lut, -method.continuous.lut, -method.continuous.min, -method.continuous.max, -method.optimal.background, -method.image.in, -method.image.low, -method.image.up, -out)

	Available options for selection parameters:

	-op(Operation)
		0 - labeltocolor
		1 - colortolabel

	-method(Color mapping method)
		0 - custom
		1 - continuous
		2 - optimal
		3 - image

	-method.continuous.lut(Look-up tables)
		0 - red
		1 - green
		2 - blue
		3 - grey
		4 - hot
		5 - cool
		6 - spring
		7 - summer
		8 - autumn
		9 - winter
		10 - copper
		11 - jet
		12 - hsv
		13 - overunder
		14 - relief
