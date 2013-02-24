SUPERIMPOSE SENSOR
==================

Description
-----------

Parameters
----------

- ``Reference input[Raster]``:
- ``The image to reproject[Raster]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``Spacing of the deformation field[Number]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:superimposesensor', -inr, -inm, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -lms, -ram, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
