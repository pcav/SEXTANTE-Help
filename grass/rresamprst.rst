R.RESAMP.RST - REINTERPOLATES USING REGULARIZED SPLINE WITH TENSION AND SMOOTHING.
==================================================================================

Description
-----------

Parameters
----------

- ``Raster layer[Raster]``:
- ``Desired east-west resolution[Number]``:
- ``Desired north-south resolution[Number]``:
- ``Use dnorm independent tension[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Output layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.resamp.rst', input, ew_res, ns_res, -t, grass_region_parameter, grass_region_cellsize_parameter, elev)
