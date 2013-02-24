R.SLOPE.ASPECT - GENERATES RASTER LAYERS OF SLOPE, ASPECT, CURVATURES AND PARTIAL DERIVATIVES FROM A ELEVATION RASTER LAYER.
============================================================================================================================

Description
-----------

Parameters
----------

- ``Elevation[Raster]``:
- ``Format for reporting the slope[Selection]``:
- ``Type of output aspect and slope layer[Selection]``:
- ``Multiplicative factor to convert elevation units to meters[Number]``:
- ``Minimum slope val. (in percent) for which aspect is computed[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output slope layer[Raster]``:
- ``Output aspect layer[Raster]``:
- ``Output profile curvature layer[Raster]``:
- ``Output tangential curvature layer[Raster]``:
- ``Output first order partial derivative dx (E-W slope) layer[Raster]``:
- ``Output first order partial derivative dy (N-S slope) layer[Raster]``:
- ``Output second order partial derivative dxx layer[Raster]``:
- ``Output second order partial derivative dyy layer[Raster]``:
- ``Output second order partial derivative dxy layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.slope.aspect', elevation, format, prec, zfactor, min_slp_allowed, grass_region_parameter, grass_region_cellsize_parameter, slope, aspect, pcurv, tcurv, dx, dy, dxx, dyy, dxy)

	Available options for selection parameters:

	format(Format for reporting the slope)
		0 - degrees
		1 - percent

	prec(Type of output aspect and slope layer)
		0 - float
		1 - double
		2 - int
