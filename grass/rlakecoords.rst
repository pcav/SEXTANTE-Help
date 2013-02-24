R.LAKE.COORDS - FILLS LAKE AT GIVEN POINT TO GIVEN LEVEL.
=========================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Water level[Number]``:
- ``Seed point coordinates[String]``:
- ``Use negative depth values for lake raster layer[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Raster layer with lake[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.lake.coords', dem, wl, xy, -n, grass_region_parameter, grass_region_cellsize_parameter, lake)
