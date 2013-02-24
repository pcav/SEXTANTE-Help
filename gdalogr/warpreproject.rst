WARP (REPROJECT)
================

Description
-----------

Parameters
----------

- ``Input layer[Raster]``:
- ``Source SRS (EPSG Code)[Crs]``:
- ``Destination SRS (EPSG Code)[Crs]``:
- ``Output file resolution in target georeferenced units (leave 0 for no change)[Number]``:
- ``Resampling method[Selection]``:
- ``Additional creation parameters[String]``:

Outputs
-------

- ``Output layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('gdalogr:warpreproject', input, source_srs, dest_srs, tr, method, extra, output)

	Available options for selection parameters:

	method(Resampling method)
		0 - near
		1 - bilinear
		2 - cubic
		3 - cubicspline
		4 - lanczos
