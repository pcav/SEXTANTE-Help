RADIOMETRIC VEGETATION
======================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Red Channel[Number]``:
- ``NIR Channel[Number]``:
- ``NDVI[Boolean]``:
- ``TNDVI[Boolean]``:
- ``RVI[Boolean]``:
- ``SAVI[Boolean]``:
- ``TSAVI[Boolean]``:
- ``MSAVI[Boolean]``:
- ``MSAVI2[Boolean]``:
- ``GEMI[Boolean]``:
- ``IPVI[Boolean]``:
- ``LAIFromNDVILog[Boolean]``:
- ``LAIFromReflLinear[Boolean]``:
- ``LAIFromNDVIFormo[Boolean]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:radiometricvegetation', -in, -ram, -channels.red, -channels.nir, -index.ndvi, -index.tndvi, -index.rvi, -index.savi, -index.tsavi, -index.msavi, -index.msavi2, -index.gemi, -index.ipvi, -index.laindvilog, -index.lairefl, -index.laindviformo, -out)
