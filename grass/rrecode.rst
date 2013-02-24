R.RECODE - RECODES CATEGORICAL RASTER MAPS.
===========================================

Description
-----------

Parameters
----------

- ``Input layer[Raster]``:
- ``File containing recode rules[File]``:
- ``Force output to 'double' raster map type (DCELL)[Boolean]``:
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

	sextante.runalg('grass:r.recode', input, rules, -d, grass_region_parameter, grass_region_cellsize_parameter, output)
