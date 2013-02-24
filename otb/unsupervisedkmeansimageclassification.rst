UNSUPERVISED KMEANS IMAGE CLASSIFICATION
========================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Validity Mask[Raster]``:
- ``Training set size[Number]``:
- ``Number of classes[Number]``:
- ``Maximum number of iterations[Number]``:
- ``Convergence threshold[Number]``:
- ``set user defined seed[Number]``:

Outputs
-------

- ``Output Image[Raster]``:
- ``Centroid filename[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:unsupervisedkmeansimageclassification', -in, -ram, -vm, -ts, -nc, -maxit, -ct, -rand, -out, -outmeans)
