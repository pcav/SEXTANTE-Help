HYPERSPECTRAL DATA UNMIXING
===========================

Description
-----------

Parameters
----------

- ``Input Image Filename[Raster]``:
- ``Input endmembers[Raster]``:
- ``Unmixing algorithm[Selection]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:hyperspectraldataunmixing', -in, -ie, -ua, -out)

	Available options for selection parameters:

	-ua(Unmixing algorithm)
		0 - ucls
		1 - ncls
		2 - isra
		3 - mdmdnmf
