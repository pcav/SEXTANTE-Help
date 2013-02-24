R.RESAMP.INTERP - RESAMPLES A RASTER MAP LAYER TO A FINER GRID USING INTERPOLATION.
===================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Interpolation method[Selection]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.resamp.interp', input, method, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	method(Interpolation method)
		0 - nearest
		1 - bilinear
		2 - bicubic
