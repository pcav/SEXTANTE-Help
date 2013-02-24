OPEN STREET MAP LAYERS IMPORTATIONS APPLICATIONS
================================================

Description
-----------

Parameters
----------

- ``Support image[Raster]``:
- ``OSM tag key[String]``:
- ``OSM tag value[String]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``option to display available key/value classes[Boolean]``:

Outputs
-------

- ``Output vector data[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:openstreetmaplayersimportationsapplications', -support, -key, -value, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -printclasses, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
