GRID DIVISION
=============

Description
-----------
This algorithm creates a new grid layer as the result of the division between 2 other grid layers. 
Parameters
----------

- ``Dividend[Raster]``: first layer (dividend)
- ``Divisor[Raster]``: second layer (divisor)

Outputs
-------

- ``Quotient[Raster]``: the resulting layer (quotient)

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:griddivision', a, b, c)
