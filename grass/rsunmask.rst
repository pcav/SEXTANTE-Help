R.SUNMASK - CALCULATES CAST SHADOW AREAS FROM SUN POSITION AND ELEVATION RASTER MAP.
====================================================================================

Description
-----------

Parameters
----------

- ``elev[Raster]``:
- ``altitude[Number]``:
- ``azimuth[Number]``:
- ``year[Number]``:
- ``month[Number]``:
- ``day[Number]``:
- ``hour[Number]``:
- ``minute[Number]``:
- ``second[Number]``:
- ``East positive, offset from GMT[Number]``:
- ``Easting coordinate (point of interest)[Number]``:
- ``Northing coordinate (point of interest)[Number]``:
- ``Don't ignore zero elevation[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.sunmask', elev, altitude, azimuth, year, month, day, hour, minute, second, timezone, east, north, -z, grass_region_parameter, grass_region_cellsize_parameter, output)
