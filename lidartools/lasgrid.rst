LASGRID
=======

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Use intensity instead of elevation[Boolean]``:
- ``Method[Selection]``:
- ``Keep first return only[Boolean]``:
- ``Keep last return only[Boolean]``:
- ``Keep single returns only[Boolean]``:
- ``Keep double returns only[Boolean]``:

Outputs
-------

- ``Output grid layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:lasgrid', input, intensity, method, first_only, last_only, single_ret_only, double_ret_only, output)

	Available options for selection parameters:

	method(Method)
		0 - -average
		1 - -lowest
		2 - -highest
		3 - -stddev
