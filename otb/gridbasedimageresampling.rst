GRID BASED IMAGE RESAMPLING
===========================

Description
-----------

Parameters
----------

- ``Input image[Raster]``:
- ``Input resampling grid[Raster]``:
- ``Grid Type[Selection]``:
- ``Upper Left X[Number]``:
- ``Upper Left Y[Number]``:
- ``Size X[Number]``:
- ``Size Y[Number]``:
- ``Pixel Size X[Number]``:
- ``Pixel Size Y[Number]``:
- ``Default value[Number]``:
- ``Interpolation[Selection]``:
- ``Radius for bicubic interpolation[Number]``:
- ``Available RAM (Mb)[Number]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:gridbasedimageresampling', -io.in, -grid.in, -grid.type, -out.ulx, -out.uly, -out.sizex, -out.sizey, -out.spacingx, -out.spacingy, -out.default, -interpolator, -interpolator.bco.radius, -ram, -io.out)

	Available options for selection parameters:

	-grid.type(Grid Type)
		0 - def
		1 - loc

	-interpolator(Interpolation)
		0 - nn
		1 - linear
		2 - bco
