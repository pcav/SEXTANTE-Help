V.SURF.RST.CVDEV - SPATIAL APPROXIMATION AND TOPOGRAPHIC ANALYSIS USING REGULARIZED SPLINE WITH TENSION.
========================================================================================================

Description
-----------

Parameters
----------

- ``Input vector layer[Vector]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Name of the raster map used as mask[Raster]``:
- ``Name of the attribute column with values to be used for approximation[TableField]``:
- ``Tension parameter[Number]``:
- ``Maximum number of points in a segment[Number]``:
- ``Minimum number of points for approximation in a segment (>segmax)[Number]``:
- ``Minimum distance between points (to remove almost identical points)[Number]``:
- ``Maximum distance between points on isoline (to insert additional points)[Number]``:
- ``Anisotropy angle (in degrees counterclockwise from East)[Number]``:
- ``Anisotropy scaling factor[Number]``:
- ``-c[leave this as True][Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Cross-validation errors[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.surf.rst.cvdev', input, where, maskmap, zcolumn, tension, segmax, npmin, dmin, dmax, theta, scalex, -c, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, cvdev)
