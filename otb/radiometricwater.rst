RADIOMETRIC WATER
=================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Blue Channel[Number]``:
- ``Green Channel[Number]``:
- ``Red Channel[Number]``:
- ``NIR Channel[Number]``:
- ``Mir Channel[Number]``:
- ``Rho860 Channel[Number]``:
- ``Rho1240 Channel[Number]``:
- ``NDWI[Boolean]``:
- ``NDWI2[Boolean]``:
- ``MNDWI[Boolean]``:
- ``NDPI[Boolean]``:
- ``NDTI[Boolean]``:
- ``SRWI[Boolean]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:radiometricwater', -in, -ram, -channels.blue, -channels.green, -channels.red, -channels.nir, -channels.mir, -channels.rho860, -channels.rho1240, -index.ndwi, -index.ndwi2, -index.mndwi, -index.ndpi, -index.ndti, -index.srwi, -out)
