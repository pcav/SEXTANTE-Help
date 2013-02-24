V.LIDAR.CORRECTION - CORRECTION OF THE V.LIDAR.GROWING OUTPUT. IT IS THE LAST OF THE THREE ALGORITHMS FOR LIDAR FILTERING.
==========================================================================================================================

Description
-----------

Parameters
----------

- ``Input vector layer (v.lidar.growing output)[Vector]``:
- ``Interpolation spline step value in east direction[String]``:
- ``Interpolation spline step value in north direction[String]``:
- ``Regularization weight in reclassification evaluation[String]``:
- ``High threshold for object to terrain reclassification[String]``:
- ``Low threshold for object to terrain reclassification[String]``:
- ``Estimate point density and distance[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output classified layer[Vector]``:
- ``Only 'terrain' points output layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.lidar.correction', input, sce, scn, lambda_c, tch, tcl, -e, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output, terrain)
