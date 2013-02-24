CONNECTED COMPONENT SEGMENTATION
================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Mask expression[String]``:
- ``Connected Component Expression[String]``:
- ``Minimum Object Size[Number]``:
- ``OBIA Expression[String]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:

Outputs
-------

- ``Output Shape[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:connectedcomponentsegmentation', -in, -mask, -expr, -minsize, -obia, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
