CREATE GRID SURFACE
===================

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Cellsize[Number]``:
- ``XY Units[Selection]``:
- ``Z Units[Selection]``:
- ``Additional modifiers[String]``:

Outputs
-------

- ``PLANS DTM surface[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:creategridsurface', input, cellsize, xyunits, zunits, advanced_modifiers, output)

	Available options for selection parameters:

	xyunits(XY Units)
		0 - Meter
		1 - Feet

	zunits(Z Units)
		0 - Meter
		1 - Feet
