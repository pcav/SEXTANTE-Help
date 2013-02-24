COMPUTE POLYLINE FEATURE FROM IMAGE
===================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Vector Data[Vector]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``Feature expression[String]``:
- ``Feature name[String]``:

Outputs
-------

- ``Output Vector Data[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:computepolylinefeaturefromimage', -in, -vd, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -expr, -field, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
