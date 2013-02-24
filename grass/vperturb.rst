V.PERTURB - RANDOM LOCATION PERTURBATIONS OF GRASS VECTOR POINTS
================================================================

Description
-----------

Parameters
----------

- ``Vector points to be spatially perturbed[Vector]``:
- ``Distribution of perturbation[Selection]``:
- ``Parameter(s) of distribution (uniform: maximum; normal: mean and stddev)[String]``:
- ``Minimum deviation in map units[Number]``:
- ``Seed for random number generation[Number]``:
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

	sextante.runalg('grass:v.perturb', input, distribution, parameters, minimum, seed, grass_region_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)

	Available options for selection parameters:

	distribution(Distribution of perturbation)
		0 - uniform
		1 - normal
