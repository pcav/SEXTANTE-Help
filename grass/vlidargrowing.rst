V.LIDAR.GROWING - BUILDING CONTOUR DETERMINATION AND REGION GROWING ALGORITHM FOR DETERMINING THE BUILDING INSIDE
=================================================================================================================

Description
-----------

Parameters
----------

- ``Input vector (v.lidar.edgedetection output)[Vector]``:
- ``First pulse vector layer[Vector]``:
- ``Threshold for cell object frequency in region growing[Number]``:
- ``Threshold for double pulse in region growing[Number]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output vector layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.lidar.growing', input, first, tj, td, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
