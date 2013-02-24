V.TO.POINTS - CREATE POINTS ALONG INPUT LINES
=============================================

Description
-----------

Parameters
----------

- ``Input lines layer[Vector]``:
- ``Maximum distance between points in map units[String]``:
- ``Write line vertices[Boolean]``:
- ``Interpolate points between line vertices[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output vector map where points will be written[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.to.points', input, dmax, -v, -i, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
