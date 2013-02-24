V.GENERALIZE - VECTOR BASED GENERALIZATION.
===========================================

Description
-----------

Parameters
----------

- ``Input layer[Vector]``:
- ``method[Selection]``:
- ``Maximal tolerance value[Number]``:
- ``Look-ahead parameter[Number]``:
- ``Percentage of the points in the output of 'douglas_reduction' algorithm[Number]``:
- ``Slide of computed point toward the original point[Number]``:
- ``Minimum angle between two consecutive segments in Hermite method[Number]``:
- ``Degree threshold in network generalization[Number]``:
- ``Closeness threshold in network generalization[Number]``:
- ``Betweeness threshold in network generalization[Number]``:
- ``Snakes alpha parameter[Number]``:
- ``Snakes beta parameter[Number]``:
- ``Number of iterations[Number]``:
- ``Copy attributes[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.generalize', input, method, threshold, look_ahead, reduction, slide, angle_thresh, degree_thresh, closeness_thresh, betweeness_thresh, alpha, beta, iterations, -c, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	method(method)
		0 - douglas
		1 - douglas_reduction
		2 - lang
		3 - reduction
		4 - reumann
		5 - remove_small
		6 - boyle
		7 - sliding_averaging
		8 - distance_weighting
		9 - chaiken
		10 - hermite
		11 - snakes
		12 - network
		13 - displacement
