R.COST - CREATES A RASTER LAYER OF CUMULATIVE COST OF MOVING ACROSS A RASTER LAYER WHOSE CELL VALUES REPRESENT COST.
====================================================================================================================

Description
-----------

Parameters
----------

- ``Unit cost layer[Raster]``:
- ``Start points[Vector]``:
- ``Stop points[Vector]``:
- ``Use the 'Knight's move'; slower, but more accurate[Boolean]``:
- ``Keep null values in output raster layer[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Cumulative cost[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.cost', input, start_points, stop_points, -k, -n, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
