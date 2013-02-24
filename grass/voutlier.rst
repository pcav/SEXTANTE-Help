V.OUTLIER - REMOVES OUTLIERS FROM VECTOR POINT DATA.
====================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Interpolation spline step value in east direction[Number]``:
- ``Interpolation spline step value in north direction[Number]``:
- ``Tykhonov regularization weight[Number]``:
- ``Threshold for the outliers[Number]``:
- ``Estimate point density and distance[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Layer without outliers[Vector]``:
- ``Outliers[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.outlier', input, soe, son, lambda_i, thres_o, -e, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output, outlier)
