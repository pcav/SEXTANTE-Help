WATERSHED SEGMENTATION (LABELED RASTER OUTPUT)
==============================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Depth Threshold[Number]``:
- ``Flood level[Number]``:

Outputs
-------

- ``Output labeled image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:watershedsegmentationlabeledrasteroutput', -filter watershed -in, -filter.watershed.threshold, -filter.watershed.level, -mode raster -mode.raster.out)
