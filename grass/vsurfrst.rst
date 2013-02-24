V.SURF.RST - SPATIAL APPROXIMATION AND TOPOGRAPHIC ANALYSIS USING REGULARIZED SPLINE WITH TENSION.
==================================================================================================

Description
-----------

Parameters
----------

- ``Input points layer[Vector]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Name of the raster map used as mask[Raster]``:
- ``Name of the attribute column with values to be used for approximation[TableField]``:
- ``Tension parameter[Number]``:
- ``Maximum number of points in a segment[Number]``:
- ``Minimum number of points for approximation in a segment (>segmax)[Number]``:
- ``Minimum distance between points (to remove almost identical points)[Number]``:
- ``Maximum distance between points on isoline (to insert additional points)[Number]``:
- ``Conversion factor for values used for approximation[Number]``:
- ``Anisotropy angle (in degrees counterclockwise from East)[Number]``:
- ``Anisotropy scaling factor[Number]``:
- ``Use scale dependent tension[Boolean]``:
- ``Output partial derivatives instead of topographic parameters[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Surface[Raster]``:
- ``Slope[Raster]``:
- ``Aspect[Raster]``:
- ``Profile curvature[Raster]``:
- ``Tangential curvature[Raster]``:
- ``Mean curvature[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.surf.rst', input, where, maskmap, zcolumn, tension, segmax, npmin, dmin, dmax, zmult, theta, scalex, -t, -d, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, elev, slope, aspect, pcurv, tcurv, mcurv)
