R.FILLNULLS - FILLS NO-DATA AREAS IN A RASTER LAYER USING V.SURF.RST SPLINES INTERPOLATION OR V.SURF.BSPLINE INTERPOLATION
==========================================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer to fill[Raster]``:
- ``Method[Selection]``:
- ``Spline tension parameter[Number]``:
- ``Spline smoothing parameter[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Filled layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.fillnulls', input, method, tension, smooth, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	method(Method)
		0 - bilinear
		1 - bicubic
		2 - rst
