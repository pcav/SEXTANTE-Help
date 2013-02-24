I.ZC - ZERO-CROSSING "EDGE DETECTION" RASTER FUNCTION FOR IMAGE PROCESSING.
===========================================================================

Description
-----------

Parameters
----------

- ``Name of input raster map[Raster]``:
- ``x-y extent of the Gaussian filter[Number]``:
- ``Sensitivity of Gaussian filter[Number]``:
- ``Number of azimuth directions categorized[Number]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Zero crossing raster map[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:i.zc', input, width, threshold, orientations, grass_region_parameter, grass_region_cellsize_parameter, output)
