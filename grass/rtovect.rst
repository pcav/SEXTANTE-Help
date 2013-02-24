R.TO.VECT - CONVERTS A RASTER INTO A VECTOR LAYER.
==================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Feature type[Selection]``:
- ``Smooth corners of area features[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output vector layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.to.vect', input, feature, -s, grass_region_parameter, output)

	Available options for selection parameters:

	feature(Feature type)
		0 - line
		1 - point
		2 - area
