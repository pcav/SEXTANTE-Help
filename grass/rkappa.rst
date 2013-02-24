R.KAPPA - CALCULATE ERROR MATRIX AND KAPPA PARAMETER FOR ACCURACY ASSESSMENT OF CLASSIFICATION RESULT.
======================================================================================================

Description
-----------

Parameters
----------

- ``Raster layer containing classification result[Raster]``:
- ``Raster layer containing reference classes[Raster]``:
- ``Title for error matrix and kappa[String]``:
- ``No header in the report[Boolean]``:
- ``Wide report (132 columns)[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output file containing error matrix and kappa[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.kappa', classification, reference, title, -h, -w, grass_region_parameter, output)
