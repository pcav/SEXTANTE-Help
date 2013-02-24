LAS2ISO
=======

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Interval between isolines[Number]``:
- ``Clean isolines shorter than (0 = do not clean)[Number]``:
- ``simplify segments shorter than (0 = do not simplify)[Number]``:
- ``Keep first return only[Boolean]``:
- ``Keep last return only[Boolean]``:
- ``Keep single returns only[Boolean]``:
- ``Keep double returns only[Boolean]``:

Outputs
-------

- ``Output isolines[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:las2iso', input, interval, clean, simplify, first_only, last_only, single_ret_only, double_ret_only, output)
