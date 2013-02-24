IMAGE ENVELOPE
==============

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Sampling Rate[Number]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``Projection[String]``:

Outputs
-------

- ``Output Vector Data[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:imageenvelope', -in, -sr, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -proj, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
