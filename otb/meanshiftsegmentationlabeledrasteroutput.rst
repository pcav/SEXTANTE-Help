MEAN SHIFT SEGMENTATION (LABELED RASTER OUTPUT)
===============================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Spatial radius[Number]``:
- ``Mode convergence threshold[Number]``:
- ``Range radius[Number]``:
- ``Min region size[Number]``:
- ``Maximum number of iterations[Number]``:

Outputs
-------

- ``Output labeled image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:meanshiftsegmentationlabeledrasteroutput', -filter meanshift -in, -filter.meanshift.spatialr, -filter.meanshift.thres, -filter.meanshift.ranger, -filter.meanshift.minsize, -filter.meanshift.maxiter, -mode raster -mode.raster.out)
