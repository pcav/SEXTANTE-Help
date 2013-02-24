VECTOR DATA TRANSFORMATION
==========================

Description
-----------

Parameters
----------

- ``Input Vector data[Vector]``:
- ``Support image[Raster]``:
- ``Translation X[Number]``:
- ``Translation Y[Number]``:
- ``Rotation Angle[Number]``:
- ``Center X[Number]``:
- ``Center Y[Number]``:
- ``Scale[Number]``:

Outputs
-------

- ``Output Vector data[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:vectordatatransformation', -vd, -in, -transform.tx, -transform.ty, -transform.ro, -transform.centerx, -transform.centery, -transform.scale, -out)
