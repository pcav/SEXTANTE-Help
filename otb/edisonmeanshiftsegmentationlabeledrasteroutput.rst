EDISON MEAN SHIFT SEGMENTATION (LABELED RASTER OUTPUT)
======================================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Spatial radius[Number]``:
- ``Range radius[Number]``:
- ``Min region size[Number]``:
- ``Scale Factor[Number]``:

Outputs
-------

- ``Output labeled image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:edisonmeanshiftsegmentationlabeledrasteroutput', -filter edison -in, -filter.edison.spatialr, -filter.edison.ranger, -filter.edison.minsize, -filter.edison.scale, -mode raster -mode.raster.out)
