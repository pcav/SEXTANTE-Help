V.VORONOI - CREATES A VORONOI DIAGRAM FROM AN INPUT VECTOR LAYER CONTAINING POINTS.
===================================================================================

Description
-----------

Parameters
----------

- ``Input points layer[Vector]``:
- ``Output tessellation as a graph (lines), not areas[Boolean]``:
- ``Do not create attribute table[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Voronoi diagram[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.voronoi', input, -l, -t, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
