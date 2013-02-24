IMAGE SVM CLASSIFICATION
========================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Input Mask[Raster]``:
- ``SVM Model file[File]``:
- ``Statistics file[File]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:imagesvmclassification', -in, -mask, -svm, -imstat, -ram, -out)
