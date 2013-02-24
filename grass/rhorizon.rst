R.HORIZON - HORIZON ANGLE COMPUTATION FROM A DIGITAL ELEVATION MODEL.
=====================================================================

Description
-----------

Parameters
----------

- ``Elevation layer [meters][Raster]``:
- ``Direction in which you want to know the horizon height[Number]``:
- ``Angle step size for multidirectional horizon [degrees][Number]``:
- ``The maximum distance to consider when finding the horizon height[Number]``:
- ``Sampling distance step coefficient (0.5-1.5)[String]``:
- ``Write output in degrees (default is radians)[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.horizon', elevin, direction, horizonstep, maxdistance, dist, -d, grass_region_parameter)
