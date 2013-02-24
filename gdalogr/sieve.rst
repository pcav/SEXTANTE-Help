SIEVE
=====

Description
-----------

Parameters
----------

- ``src filename[Raster]``:
- ``connectedness[Selection]``:
- ``threshold[Number]``:

Outputs
-------

- ``dst_filename[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('gdalogr:sieve', src_filename, connectedness, threshold, dst_filename)

	Available options for selection parameters:

	connectedness(connectedness)
		0 -  4
		1 - 8
