R.DESCRIBE - PRINTS TERSE LIST OF CATEGORY VALUES FOUND IN A RASTER LAYER.
==========================================================================

Description
-----------

Parameters
----------

- ``input raster layer[Raster]``:
- ``No-data cell value[Number]``:
- ``Number of quantization steps[Number]``:
- ``Only print the range of the data[Boolean]``:
- ``Suppress reporting of any NULLs[Boolean]``:
- ``Use the current region[Boolean]``:
- ``Read fp map as integer[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output report[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.describe', map, nv, nsteps, -r, -n, -d, -i, grass_region_parameter, html)
