R.MFILTER.FP - RASTER MAP MATRIX FILTER.
========================================

Description
-----------

Parameters
----------

- ``input layer[Raster]``:
- ``Filter file[File]``:
- ``Number of times to repeat the filter[Number]``:
- ``Apply filter only to zero data values[Boolean]``:
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

	sextante.runalg('grass:r.mfilter.fp', input, filter, repeat, -z, grass_region_parameter, grass_region_cellsize_parameter, output)
