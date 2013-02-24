R.PARAM.SCALE - EXTRACTS TERRAIN PARAMETERS FROM A DEM.
=======================================================

Description
-----------

Parameters
----------

- ``Name of input raster map[Raster]``:
- ``Slope tolerance that defines a 'flat' surface (degrees)[Number]``:
- ``Curvature tolerance that defines 'planar' surface[Number]``:
- ``Size of processing window (odd number only, max: 69)[Number]``:
- ``Morphometric parameter in 'size' window to calculate[Selection]``:
- ``Exponent for distance weighting (0.0-4.0)[Number]``:
- ``Vertical scaling factor[Number]``:
- ``Constrain model through central window cell[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output raster layer containing morphometric parameter[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.param.scale', input, s_tol, c_tol, size, param, exp, zscale, -c, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	param(Morphometric parameter in 'size' window to calculate)
		0 - elev
		1 - slope
		2 - aspect
		3 - profc
		4 - planc
		5 - longc
		6 - crosc
		7 - minic
		8 - maxic
		9 - feature
