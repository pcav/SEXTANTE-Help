V.NEIGHBORS - MAKES EACH CELL VALUE A FUNCTION OF ATTRIBUTE VALUES AND STORES IN AN OUTPUT RASTER MAP.
======================================================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Neighborhood diameter in map units[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.neighbors', input, size, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
