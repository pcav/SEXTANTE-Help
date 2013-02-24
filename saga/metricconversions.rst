METRIC CONVERSIONS
==================

Description
-----------

Parameters
----------

- ``Grid[Raster]``:
- ``Conversion[Selection]``:

Outputs
-------

- ``Converted Grid[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:metricconversions', grid, conversion, conv)

	Available options for selection parameters:

	conversion(Conversion)
		0 - [0] radians to degree
		1 - [1] degree to radians
		2 - [2] Celsius to Fahrenheit
		3 - [3] Fahrenheit to Celsius
