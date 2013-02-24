SMOOTHING
=========

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Smoothing Type[Selection]``:
- ``Radius[Number]``:
- ``Radius[Number]``:
- ``Time Step[Number]``:
- ``Nb Iterations[Number]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:smoothing', -in, -ram, -type, -type.mean.radius, -type.gaussian.radius, -type.anidif.timestep, -type.anidif.nbiter, -out)

	Available options for selection parameters:

	-type(Smoothing Type)
		0 - mean
		1 - gaussian
		2 - anidif
