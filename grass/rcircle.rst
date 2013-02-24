R.CIRCLE - CREATES A RASTER MAP CONTAINING CONCENTRIC RINGS AROUND A GIVEN POINT.
=================================================================================

Description
-----------

Parameters
----------

- ``The coordinate of the center (east,north)[String]``:
- ``Minimum radius for ring/circle map (in meters)[Number]``:
- ``Maximum radius for ring/circle map (in meters)[Number]``:
- ``Data value multiplier[String]``:
- ``Generate binary raster map[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name for output raster map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.circle', coordinate, min, max, mult, -b, grass_region_parameter, grass_region_cellsize_parameter, output)
