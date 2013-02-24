TRAIN SVM CLASSIFIER FROM MULTIPLE IMAGES
=========================================

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
- ``Maximum training sample size[Number]``:
- ``Maximum validation sample size[Number]``:
- ``On edge pixel inclusion[Boolean]``:
- ``training and validation sample ratio[Number]``:
- ``Name of the discrimination field[String]``:
- ``SVM Kernel Type[Selection]``:
- ``Cost parameter C.[Number]``:
- ``parameters optimization[Boolean]``:
- ``set user defined seed[Number]``:

Outputs
-------

- ``Output SVM model[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('otb:trainsvmclassifierfrommultipleimages', -io.il, -io.vd, -io.imstat, -elev, -elev.dem.path, -elev.dem.geoid, -elev.average.value, -sample.mt, -sample.mv, -sample.edg, -sample.vtr, -sample.vfn, -svm.k, -svm.c, -svm.opt, -rand, -io.out)

	Available options for selection parameters:

	-elev(Elevation management)
		0 - dem
		1 - average

	-svm.k(SVM Kernel Type)
		0 - linear
		1 - rbf
		2 - poly
		3 - sigmoid
