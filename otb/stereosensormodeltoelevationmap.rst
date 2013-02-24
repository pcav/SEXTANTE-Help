STEREO SENSOR MODEL TO ELEVATION MAP
====================================

Description
-----------

Parameters
----------

- ``Reference[Raster]``:
- ``Secondary[Raster]``:
- ``Available RAM (Mb)[Number]``:
- ``Radius[Number]``:
- ``Correlation Threshold[Number]``:
- ``Variance Threshold[Number]``:
- ``MinHeightOffset[Number]``:
- ``MaxHeightOffset[Number]``:
- ``HeightStep[Number]``:
- ``AverageElevation[Number]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``ReferenceGaussianSmoothing[Number]``:
- ``SecondaryGaussianSmoothing[Number]``:
- ``SubtractInitialHeight[Boolean]``:

Outputs
-------

- ``Output Image[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:stereosensormodeltoelevationmap', -ref, -sec, -ram, -r, -ct, -vt, -minh, -maxh, -step, -ae, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -rgs, -sgs, -s, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
