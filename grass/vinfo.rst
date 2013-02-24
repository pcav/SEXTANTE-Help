V.INFO - OUTPUTS BASIC INFORMATION ABOUT A USER-SPECIFIED VECTOR MAP.
=====================================================================

Description
-----------

Parameters
----------

- ``Name of input vector map[Vector]``:
- ``Print types/names of table columns for specified layer instead of info[Boolean]``:
- ``Print map region only[Boolean]``:
- ``Print topology information only[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Info file[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.info', map, -c, -g, -t, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, html)
