LASGROUND
=========

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Method[Selection]``:
- ``Keep first return only[Boolean]``:
- ``Keep last return only[Boolean]``:
- ``Keep single returns only[Boolean]``:
- ``Keep double returns only[Boolean]``:

Outputs
-------

- ``Output ground las file[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:lasground', input, method, first_only, last_only, single_ret_only, double_ret_only, output)

	Available options for selection parameters:

	method(Method)
		0 - terrain
		1 - town
		2 - city
