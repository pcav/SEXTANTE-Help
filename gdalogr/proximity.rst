PROXIMITY
=========

Description
-----------

Parameters
----------

- ``src filename[Raster]``:
- ``values[String]``:
- ``maxdist[Number]``:
- ``nodata[Number]``:
- ``distunits[Selection]``:
- ``fixed buf val[Number]``:

Outputs
-------

- ``dst_filename[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('gdalogr:proximity', src_filename, values, maxdist, nodata, distunits, fixed_buf_val, dst_filename)

	Available options for selection parameters:

	distunits(distunits)
		0 -  PIXEL
		1 - GEO
