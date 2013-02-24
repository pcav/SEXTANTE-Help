R.WATER.OUTLET - WATERSHED BASIN CREATION PROGRAM.
==================================================

Description
-----------

Parameters
----------

- ``Name of input raster map[Raster]``:
- ``Easting coordinate of outlet point[Number]``:
- ``Northing coordinate of outlet point[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output basin layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.water.outlet', drainage, easting, northing, grass_region_parameter, grass_region_cellsize_parameter, basin)
