R.GWFLOW - NUMERICAL CALCULATION PROGRAM FOR TRANSIENT, CONFINED AND UNCONFINED GROUNDWATER FLOW IN TWO DIMENSIONS.
===================================================================================================================

Description
-----------

Parameters
----------

- ``The initial piezometric head in [m][String]``:
- ``Boundary condition status, 0-inactive, 1-active, 2-dirichlet[String]``:
- ``X-part of the hydraulic conductivity tensor in [m/s][String]``:
- ``Y-part of the hydraulic conductivity tensor in [m/s][String]``:
- ``Water sources and sinks in [m^3/s][String]``:
- ``Specific yield in [1/m][String]``:
- ``Recharge map e.g: 6*10^-9 per cell in [m^3/s*m^2][String]``:
- ``Top surface of the aquifer in [m][String]``:
- ``Bottom surface of the aquifer in [m][String]``:
- ``The type of groundwater flow[Selection]``:
- ``The height of the river bed in [m][String]``:
- ``Water level (head) of the river with leakage connection in [m][String]``:
- ``The leakage coefficient of the river bed in [1/s][String]``:
- ``The height of the drainage bed in [m][String]``:
- ``The leakage coefficient of the drainage bed in [1/s][String]``:
- ``The calculation time in seconds[Number]``:
- ``Maximum number of iteration used to solver the linear equation system[Number]``:
- ``Error break criteria for iterative solvers (jacobi, sor, cg or bicgstab)[Number]``:
- ``The type of solver which should solve the symmetric linear equation system[Selection]``:
- ``The relaxation parameter used by the jacobi and sor solver for speedup or stabilizing[String]``:
- ``Use a sparse matrix, only available with iterative solvers[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``The map storing the numerical result [m][Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.gwflow', phead, status, hc_x, hc_y, q, s, r, top, bottom, type, river_bed, river_head, river_leak, drain_bed, drain_leak, dt, maxit, error, solver, relax, -s, grass_region_parameter, grass_region_cellsize_parameter, output)

	Available options for selection parameters:

	type(The type of groundwater flow)
		0 - confined
		1 - unconfined

	solver(The type of solver which should solve the symmetric linear equation system)
		0 - gauss
		1 - lu
		2 - cholesky
		3 - jacobi
		4 - sor
		5 - cg
		6 - bicgstab
		7 - pcg
