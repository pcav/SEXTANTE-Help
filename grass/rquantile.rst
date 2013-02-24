R.QUANTILE - COMPUTE QUANTILES USING TWO PASSES.
================================================

Description
-----------

Parameters
----------

- ``Input raster layer[Raster]``:
- ``Number of quantiles[Number]``:
- ``Generate recode rules based on quantile-defined intervals[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output report[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.quantile', input, quantiles, -r, grass_region_parameter, html)
