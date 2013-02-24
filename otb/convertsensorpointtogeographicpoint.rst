CONVERT SENSOR POINT TO GEOGRAPHIC POINT
========================================

Description
-----------

Parameters
----------

- ``Sensor image[Raster]``:
- ``X value of desired point[Number]``:
- ``Y value of desired point[Number]``:
- ``Output Point Longitude[Number]``:
- ``Output Point Latitude[Number]``:
- ``Main town near the coordinates computed[String]``:
- ``Country of the image[String]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('otb:convertsensorpointtogeographicpoint', -in, -input.idx, -input.idy, -output.idx, -output.idy, -output.town, -output.country)
