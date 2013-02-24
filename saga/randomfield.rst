RANDOM FIELD
============

Description
-----------

Parameters
----------

- ``Width (Cells)[Number]``:
- ``Height (Cells)[Number]``:
- ``Cellsize[Number]``:
- ``West[Number]``:
- ``South[Number]``:
- ``Method[Selection]``:
- ``Range Min[Number]``:
- ``Range Max[Number]``:
- ``Arithmetic Mean[Number]``:
- ``Standard Deviation[Number]``:

Outputs
-------

- ``Random Field[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:randomfield', nx, ny, cellsize, xmin, ymin, method, range_min, range_max, mean, stddev, output)

	Available options for selection parameters:

	method(Method)
		0 - [0] Uniform
		1 - [1] Gaussian
