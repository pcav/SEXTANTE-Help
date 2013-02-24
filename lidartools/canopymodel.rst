CANOPY MODEL
============

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Input ground DTM layer [optional, leave blank if not using it][File]``:
- ``Cellsize[Number]``:
- ``XY Units[Selection]``:
- ``Z Units[Selection]``:
- ``Additional modifiers[String]``:

Outputs
-------

- ``Canopy model[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:canopymodel', input, ground, cellsize, xyunits, zunits, advanced_modifiers, output)

	Available options for selection parameters:

	xyunits(XY Units)
		0 - Meter
		1 - Feet

	zunits(Z Units)
		0 - Meter
		1 - Feet
