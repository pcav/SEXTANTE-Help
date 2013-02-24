VECTORDATA EXTRACT ROI
======================

Description
-----------

Parameters
----------

- ``Input Vector data[Vector]``:
- ``Support image[Raster]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:

Outputs
-------

- ``Output Vector data[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:vectordataextractroi', -io.vd, -io.in, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -io.out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
