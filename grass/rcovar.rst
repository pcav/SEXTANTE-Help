R.COVAR - OUTPUTS A COVARIANCE/CORRELATION MATRIX FOR USER-SPECIFIED RASTER LAYER(S).
=====================================================================================

Description
-----------

Parameters
----------

- ``Input layers[MultipleInput]``:
- ``Print correlation matrix[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Covariance report[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.covar', map, -r, grass_region_parameter, html)
