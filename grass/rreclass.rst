R.RECLASS - CREATES A NEW MAP LAYER WHOSE CATEGORY VALUES ARE BASED UPON A RECLASSIFICATION OF THE CATEGORIES IN AN EXISTING RASTER MAP LAYER.
==============================================================================================================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``File containing reclass rules[File]``:
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

	sextante.runalg('grass:r.reclass', input, rules, grass_region_parameter, grass_region_cellsize_parameter, output)
