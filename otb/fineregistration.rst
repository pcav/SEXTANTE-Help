FINE REGISTRATION
=================

Description
-----------

Parameters
----------

- ``Reference Image[Raster]``:
- ``Secondary Image[Raster]``:
- ``Exploration Radius X[Number]``:
- ``Exploration Radius Y[Number]``:
- ``Metric Radius X[Number]``:
- ``Metric Radius Y[Number]``:
- ``Image To Warp[Raster]``:
- ``Coarse Offset X[Number]``:
- ``Coarse Offset Y[Number]``:
- ``Sub-Sampling Rate X[Number]``:
- ``Sub-Sampling Rate Y[Number]``:
- ``Reference Gaussian Smoothing X[Number]``:
- ``Reference Gaussian Smoothing Y[Number]``:
- ``Secondary Gaussian Smoothing X[Number]``:
- ``Secondary Gaussian Smoothing Y[Number]``:
- ``Metric[String]``:
- ``SubPixelAccuracy[Number]``:
- ``Validity Mask Lower Threshold[Number]``:
- ``Validity Mask Upper Threshold[Number]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output Image[Raster]``:
- ``Output Warped Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:fineregistration', -ref, -sec, -erx, -ery, -mrx, -mry, -w, -cox, -coy, -ssrx, -ssry, -rgsx, -rgsy, -sgsx, -sgsy, -m, -spa, -vmlt, -vmut, -ram, -out, -wo)
