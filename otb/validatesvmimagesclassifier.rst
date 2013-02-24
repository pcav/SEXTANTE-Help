VALIDATE SVM IMAGES CLASSIFIER
==============================

Description
-----------

Parameters
----------

- ``Input Image List[MultipleInput]``:
- ``Vector Data List[MultipleInput]``:
- ``XML image statistics file[File]``:
- ``Elevation management[Selection]``:
- ``DEM directory[File]``:
- ``Geoid File[File]``:
- ``Average Elevation[Number]``:
- ``SVM validation filename[File]``:
- ``set user defined seed[Number]``:

Outputs
-------

- ``Output filename[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:validatesvmimagesclassifier', -il, -vd, -imstat, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -svm, -rand, -out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average
