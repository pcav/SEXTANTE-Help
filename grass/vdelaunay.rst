V.DELAUNAY - CREATES A DELAUNAY TRIANGULATION FROM AN INPUT VECTOR MAP CONTAINING POINTS OR CENTROIDS.
======================================================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Use only points in current region[Boolean]``:
- ``Output triangulation as a graph (lines), not areas[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Delaunay triangulation[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.delaunay', input, -r, -l, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
