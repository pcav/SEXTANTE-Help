R.REGRESSION.LINE - CALCULATES LINEAR REGRESSION FROM TWO RASTER LAYERS : Y = A + B*X.
======================================================================================

Description
-----------

Parameters
----------

- ``Layer for x coefficient[Raster]``:
- ``Layer for y coefficient[Raster]``:
- ``Slower but accurate[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Regression data[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.regression.line', map1, map2, -s, grass_region_parameter, html)
