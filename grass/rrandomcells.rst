R.RANDOM.CELLS - GENERATES RANDOM CELL VALUES WITH SPATIAL DEPENDENCE.
======================================================================

Description
-----------

Parameters
----------

- ``Maximum distance of spatial correlation (value(s) >= 0.0)[Number]``:
- ``Random seed (SEED_MIN >= value >= SEED_MAX) (default [random])[Number]``:
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

	sextante.runalg('grass:r.random.cells', distance, seed, grass_region_parameter, grass_region_cellsize_parameter, output)
