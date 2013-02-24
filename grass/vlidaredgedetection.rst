V.LIDAR.EDGEDETECTION - DETECTS THE OBJECT'S EDGES FROM A LIDAR DATA SET.
=========================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Interpolation spline step value in east direction[String]``:
- ``Interpolation spline step value in north direction[String]``:
- ``Regularization weight in gradient evaluation[String]``:
- ``High gradient threshold for edge classification[String]``:
- ``Low gradient threshold for edge classification[String]``:
- ``Angle range for same direction detection[String]``:
- ``Regularization weight in residual evaluation[String]``:
- ``Estimate point density and distance[Boolean]``:
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

	sextante.runalg('grass:v.lidar.edgedetection', input, see, sen, lambda_g, tgh, tgl, theta_g, lambda_r, -e, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
