R.PLANE - CREATES RASTER PLANE LAYER GIVEN DIP (INCLINATION), ASPECT (AZIMUTH) AND ONE POINT.
=============================================================================================

Description
-----------

Parameters
----------

- ``Dip of plane. Value must be between -90 and 90 degrees[Number]``:
- ``Azimuth of the plane. Value must be between 0 and 360 degrees[Number]``:
- ``Easting coordinate of a point on the plane[Number]``:
- ``Northing coordinate of a point on the plane[Number]``:
- ``Elevation coordinate of a point on the plane[Number]``:
- ``Data type of resulting layer[Selection]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.plane', dip, azimuth, easting, northing, elevation, type, grass_region_parameter, grass_region_cellsize_parameter, name)

	Available options for selection parameters:

	type(Data type of resulting layer)
		0 - int
		1 - float
		2 - double
