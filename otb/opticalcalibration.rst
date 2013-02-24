OPTICAL CALIBRATION
===================

Description
-----------

Parameters
----------

- ``Input[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Calibration Level[Selection]``:
- ``Convert to milli reflectance[Boolean]``:
- ``Relative Spectral Response File[File]``:
- ``Aerosol Model[Selection]``:
- ``Ozone Amount[Number]``:
- ``Water Vapor Amount[Number]``:
- ``Atmospheric Pressure[Number]``:
- ``Aerosol Optical Thickness[Number]``:
- ``Aeronet File[File]``:
- ``Window radius[Number]``:

Outputs
-------

- ``Output[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:opticalcalibration', -in, -ram, -level, -milli, -rsr, -atmo.aerosol, -atmo.oz, -atmo.wa, -atmo.pressure, -atmo.opt, -atmo.aeronet, -radius, -out)

	Available options for selection parameters:

	-level(Calibration Level)
		0 - toa
		1 - toc

	-atmo.aerosol(Aerosol Model)
		0 - noaersol
		1 - continental
		2 - maritime
		3 - urban
		4 - desertic
