V.SURF.BSPLINE - BICUBIC OR BILINEAR SPLINE INTERPOLATION WITH TYKHONOV REGULARIZATION.
=======================================================================================

Description
-----------

Parameters
----------

- ``Input points layer[Vector]``:
- ``Input layer of sparse points[Vector]``:
- ``Length of each spline step in the east-west direction[Number]``:
- ``Length of each spline step in the north-south direction[Number]``:
- ``Spline interpolation algorithm[Selection]``:
- ``Tykhonov regularization parameter (affects smoothing)[Number]``:
- ``Attribute table column with values to interpolate[TableField]``:
- ``Find the best Tykhonov regularizing parameter using a "leave-one-out" cross validation method[Boolean]``:
- ``Estimate point density and distance[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output vector layer[Vector]``:
- ``Output raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.surf.bspline', input, sparse, sie, sin, method, lambda_i, column, -c, -e, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output, raster)

	Available options for selection parameters:

	method(Spline interpolation algorithm)
		0 - bilinear
		1 - bicubic
