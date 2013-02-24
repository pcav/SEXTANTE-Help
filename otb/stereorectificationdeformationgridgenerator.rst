STEREO-RECTIFICATION DEFORMATION GRID GENERATOR
===============================================

Description
-----------

Parameters
----------

- ``Left input image[Raster]``:
- ``Right input image[Raster]``:
- ``Elevation management[Selection]``:
- ``Average elevation value[Number]``:
- ``DEM directory[File]``:
- ``Geoid file[File]``:
- ``Sub-sampling step[Number]``:
- ``Average elevation value[Number]``:
- ``Minimum disparity from DEM[Number]``:
- ``Maximum disparity from DEM[Number]``:
- ``DEM directory[File]``:
- ``Geoid file[File]``:
- ``Scale of epipolar images[Number]``:
- ``Step of the deformation grid (in nb. of pixels)[Number]``:
- ``Rectified image size X[Number]``:
- ``Rectified image size Y[Number]``:
- ``Mean baseline ratio[Number]``:
- ``Sub-sampling rate for inversion[Number]``:

Outputs
-------

- ``Left output deformation grid[Raster]``:
- ``Right output deformation grid[Raster]``:
- ``Left inverse deformation grid[Raster]``:
- ``Right inverse deformation grid[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:stereorectificationdeformationgridgenerator', -io.inleft, -io.inright, -epi.elevation, -epi.elevation.avg.value, -epi.elevation.avgdem.path, -epi.elevation.avgdem.geoid, -epi.elevation.avgdem.step, -epi.elevation.avgdem.value, -epi.elevation.avgdem.mindisp, -epi.elevation.avgdem.maxdisp, -epi.elevation.dem.path, -epi.elevation.dem.geoid, -epi.scale, -epi.step, -epi.rectsizex, -epi.rectsizey, -epi.baseline, -inverse.ssrate, -io.outleft, -io.outright, -inverse.outleft, -inverse.outright)

	Available options for selection parameters:

	-epi.elevation(Elevation management)
		0 - avg
		1 - avgdem
		2 - dem
