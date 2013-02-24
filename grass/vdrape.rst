V.DRAPE - CONVERTS VECTOR MAP TO 3D BY SAMPLING OF ELEVATION RASTER MAP.
========================================================================

Description
-----------

Parameters
----------

- ``Iput vector layer[Vector]``:
- ``Elevation raster map for height extraction[Raster]``:
- ``Sampling method[Selection]``:
- ``Scale factor for sampled raster values[String]``:
- ``WHERE conditions of SQL statement without 'where' keyword[String]``:
- ``Vector Z value for unknown height[String]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.drape', input, rast, method, scale, where, null_value, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	method(Sampling method)
		0 - nearest
		1 - bilinear
		2 - cubic
