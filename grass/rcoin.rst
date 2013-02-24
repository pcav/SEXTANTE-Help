R.COIN - TABULATES THE MUTUAL OCCURRENCE (COINCIDENCE) OF CATEGORIES FOR TWO RASTER MAP LAYERS.
===============================================================================================

Description
-----------

Parameters
----------

- ``Name of first raster map[Raster]``:
- ``Name of second raster map[Raster]``:
- ``Unit of measure[Selection]``:
- ``Wide report, 132 columns (default: 80)[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output report[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.coin', map1, map2, units, -w, grass_region_parameter, html)

	Available options for selection parameters:

	units(Unit of measure)
		0 - c
		1 - p
		2 - x
		3 - y
		4 - a
		5 - h
		6 - k
		7 - m
