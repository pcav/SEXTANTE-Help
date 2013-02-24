HOOVER COMPARE SEGMENTATION
===========================

Description
-----------

Parameters
----------

- ``Input ground truth[Raster]``:
- ``Input machine segmentation[Raster]``:
- ``Background label[Number]``:
- ``Overlapping threshold[Number]``:
- ``Correct detection score[Number]``:
- ``Over-segmentation score[Number]``:
- ``Under-segmentation score[Number]``:
- ``Missed detection score[Number]``:

Outputs
-------

- ``Colored ground truth output[Raster]``:
- ``Colored machine segmentation output[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:hoovercomparesegmentation', -ingt, -inms, -bg, -th, -rc, -rf, -ra, -rm, -outgt, -outms)
