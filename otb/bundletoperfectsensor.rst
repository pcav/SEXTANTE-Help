BUNDLE TO PERFECT SENSOR
========================

Description
-----------

Parameters
----------

- ``Input PAN Image[Raster]``:
- ``Input XS Image[Raster]``:
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

	sextante.runalg('otb:bundletoperfectsensor', -inp, -inxs, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -lms, -ram, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
