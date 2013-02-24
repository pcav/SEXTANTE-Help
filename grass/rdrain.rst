R.DRAIN - TRACES A FLOW THROUGH AN ELEVATION MODEL ON A RASTER MAP.
===================================================================

Description
-----------

Parameters
----------

- ``Elevatio[Raster]``:
- ``Map coordinates of starting point(s) (E,N)[String]``:
- ``Vector layer(s) containing starting point(s)[MultipleInput]``:
- ``Copy input cell values on output[Boolean]``:
- ``Accumulate input values along the path[Boolean]``:
- ``Count cell numbers along the path[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Result[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.drain', input, coordinate, vector_points, -c, -a, -n, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
