LINE SEGMENT DETECTION
======================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``No rescaling in [0, 255][Boolean]``:

Outputs
-------

- ``Output Detected lines[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:linesegmentdetection', -in, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -norescale, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
