R.CARVE - TAKES VECTOR STREAM DATA, TRANSFORMS IT TO RASTER AND SUBTRACTS DEPTH FROM THE OUTPUT DEM.
====================================================================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Vector layer containing stream(s)[Vector]``:
- ``Stream width (in meters). Default is raster cell width[Number]``:
- ``Additional stream depth (in meters)[Number]``:
- ``No flat areas allowed in flow direction[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Modified elevation[Raster]``:
- ``Adjusted stream points[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.carve', rast, vect, width, depth, -n, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output, points)
