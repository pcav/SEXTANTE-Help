MEAN SHIFT FILTERING
====================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Spatial radius[Number]``:
- ``Range radius[Number]``:
- ``Mode convergence threshold[Number]``:
- ``Maximum number of iterations[Number]``:
- ``Mode search.[Boolean]``:

Outputs
-------

- ``Filtered output[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:meanshiftfiltering', -in, -spatialr, -ranger, -thres, -maxiter, -modesearch, -fout)
