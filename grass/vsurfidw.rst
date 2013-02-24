V.SURF.IDW - SURFACE INTERPOLATION FROM VECTOR POINT DATA BY INVERSE DISTANCE SQUARED WEIGHTING.
================================================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``Number of interpolation points[Number]``:
- ``Power parameter; greater values assign greater influence to closer points[Number]``:
- ``Attribute table column with values to interpolate[TableField]``:
- ``Don't index points by raster cell[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output raster[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.surf.idw', input, npoints, power, column, -n, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
