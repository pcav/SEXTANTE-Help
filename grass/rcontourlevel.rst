R.CONTOUR.LEVEL - CREATE VECTOR CONTOUR FROM RASTER AT SPECIFIED LEVELS
=======================================================================

Description
-----------

Parameters
----------

- ``Input raster[Raster]``:
- ``List of contour levels[String]``:
- ``Minimum number of points for a contour line (0 -> no limit)[String]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Contours[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.contour.level', input, levels, cut, grass_region_parameter, output)
