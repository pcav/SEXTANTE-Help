LASBOUNDARY
===========

Description
-----------

Parameters
----------

- ``Input las layer[File]``:
- ``Concavity threshold[Number]``:
- ``Compute also interior holes[Boolean]``:
- ``Compute disjoint hull[Boolean]``:
- ``Keep first return only[Boolean]``:
- ``Keep last return only[Boolean]``:
- ``Keep single returns only[Boolean]``:
- ``Keep double returns only[Boolean]``:

Outputs
-------

- ``Output boundary layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('lidartools:lasboundary', input, concavity, holes, disjoint, first_only, last_only, single_ret_only, double_ret_only, output)
