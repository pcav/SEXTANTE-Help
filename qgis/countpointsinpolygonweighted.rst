COUNT POINTS IN POLYGON(WEIGHTED)
=================================

Description
-----------

Parameters
----------

- ``Polygons[Vector]``:
- ``Points[Vector]``:
- ``Weight field[TableField]``:
- ``Count field name[String]``:

Outputs
-------

- ``Result[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('qgis:countpointsinpolygonweighted', polygons, points, weight, field, output)
