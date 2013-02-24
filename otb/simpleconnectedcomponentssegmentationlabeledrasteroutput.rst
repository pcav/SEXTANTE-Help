SIMPLE CONNECTED COMPONENTS SEGMENTATION (LABELED RASTER OUTPUT)
================================================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Condition[String]``:

Outputs
-------

- ``Output labeled image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:simpleconnectedcomponentssegmentationlabeledrasteroutput', -filter cc -in, -filter.cc.expr, -mode raster -mode.raster.out)
