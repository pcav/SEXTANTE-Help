COVER
=====

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Input ground DTM layer[File]``:
- ``Cellsize[Number]``:
- ``Heightbreak[Number]``:
- ``XY Units[Selection]``:
- ``Z Units[Selection]``:
- ``Additional modifiers[String]``:

Outputs
-------

- ``Cover[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:cover', input, ground, cellsize, heightreak, xyunits, zunits, advanced_modifiers, output)

	Available options for selection parameters:

	xyunits(XY Units)
		0 - Meter
		1 - Feet

	zunits(Z Units)
		0 - Meter
		1 - Feet
