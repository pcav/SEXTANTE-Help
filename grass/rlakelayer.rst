R.LAKE.LAYER - FILLS LAKE AT GIVEN POINT TO GIVEN LEVEL.
========================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Water level[Number]``:
- ``Raster layer with starting point(s) (at least 1 cell > 0)[Raster]``:
- ``Use negative depth values for lake raster layer[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster map with lake[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.lake.layer', dem, wl, seed, -n, grass_region_parameter, grass_region_cellsize_parameter, lake)
