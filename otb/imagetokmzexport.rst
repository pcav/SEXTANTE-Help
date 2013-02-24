IMAGE TO KMZ EXPORT
===================

Description
-----------

Parameters
----------

- ``Input image[Raster]``:
- ``Tile Size[Number]``:
- ``Image logo[Raster]``:
- ``Image legend[Raster]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:

Outputs
-------

- ``Output .kmz product[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:imagetokmzexport', -in, -tilesize, -logo, -legend, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
