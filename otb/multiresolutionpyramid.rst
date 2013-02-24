MULTI RESOLUTION PYRAMID
========================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Number Of Levels[Number]``:
- ``Subsampling factor[Number]``:
- ``Variance factor[Number]``:
- ``Use Fast Scheme[Boolean]``:

Outputs
-------

- ``Output Image[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:multiresolutionpyramid', -in, -ram, -level, -sfactor, -vfactor, -fast, -out)
