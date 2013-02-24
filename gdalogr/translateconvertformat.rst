TRANSLATE (CONVERT FORMAT)
==========================

Description
-----------

Parameters
----------

- ``Input layer[Raster]``:
- ``Set the size of the output file (In pixels or %)[Number]``:
- ``Output size is a percentage of input size[Boolean]``:
- ``Nodata value, leave as none to take the nodata value from input[String]``:
- ``Expand[Selection]``:
- ``Override the projection for the output file[Crs]``:
- ``Subset based on georeferenced coordinates[Extent]``:
- ``Copy all subdatasets of this file to individual output files[Boolean]``:
- ``Additional creation parameters[String]``:

Outputs
-------

- ``Output layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('gdalogr:translateconvertformat', input, outsize, outsize_perc, no_data, expand, srs, projwin, sds, extra, output)

	Available options for selection parameters:

	expand(Expand)
		0 - none
		1 - gray
		2 - rgb
		3 - rgba
