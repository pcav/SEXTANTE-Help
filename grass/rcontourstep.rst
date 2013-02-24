R.CONTOUR.STEP - CREATE VECTOR CONTOURS FROM RASTER AT SPECIFIED STEPS
======================================================================

Description
-----------

Parameters
----------

- ``Input raster[Raster]``:
- ``Minimum contour level[String]``:
- ``Maximum contour level[String]``:
- ``Increment between contour levels[String]``:
- ``Minimum number of points for a contour line (0 -> no limit)[String]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``contours[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.contour.step', input, minlevel, maxlevel, step, cut, grass_region_parameter, output)
