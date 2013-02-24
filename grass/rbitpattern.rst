R.BITPATTERN - COMPARES BIT PATTERNS WITH A RASTER MAP.
=======================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Bit pattern position(s)[String]``:
- ``Bit pattern value[String]``:
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

	sextante.runalg('grass:r.bitpattern', input, pattern, patval, grass_region_parameter, grass_region_cellsize_parameter, output)
