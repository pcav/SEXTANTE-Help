R.LOS - LINE-OF-SIGHT RASTER ANALYSIS PROGRAM.
==============================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Coordinate identifying the viewing position[String]``:
- ``Binary (1/0) raster layer to use as a mask[Raster]``:
- ``Viewing position height above the ground[String]``:
- ``Maximum distance from the viewing point (meters)[String]``:
- ``Consider earth curvature (current ellipsoid)[Boolean]``:
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

	sextante.runalg('grass:r.los', input, coordinate, patt_map, obs_elev, max_dist, -c, grass_region_parameter, grass_region_cellsize_parameter, output)
