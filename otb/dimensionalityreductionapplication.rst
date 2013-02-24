DIMENSIONALITY REDUCTION APPLICATION
====================================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Output min value[Number]``:
- ``Output max value[Number]``:
- ``Algorithm[Selection]``:
- ``Set the x radius of the sliding window.[Number]``:
- ``Set the y radius of the sliding window.[Number]``:
- ``number of iterations [Number]``:
- ``Give the increment weight of W in [0, 1][Number]``:
- ``Number of Components.[Number]``:
- ``Normalize.[Boolean]``:

Outputs
-------

- ``Output Image[Raster]``:
- `` Inverse Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:dimensionalityreductionapplication', -in, -rescale.outmin, -rescale.outmax, -method, -method.napca.radiusx, -method.napca.radiusy, -method.ica.iter, -method.ica.mu, -nbcomp, -normalize, -out, -outinv)

	Available options for selection parameters:

	-method(Algorithm)
		0 - pca
		1 - napca
		2 - maf
		3 - ica
