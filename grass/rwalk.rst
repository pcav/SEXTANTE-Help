R.WALK - OUTPUTS A RASTER LAYER SHOWING THE ANISOTROPIC CUMULATIVE COST OF MOVING BASED ON FRICTION COST.
=========================================================================================================

Description
-----------

Parameters
----------

- ``Elevation raster layer[Raster]``:
- ``Friction costs layer[Raster]``:
- ``Starting points[Vector]``:
- ``An optional maximum cumulative cost[String]``:
- ``Percent of map to keep in memory[String]``:
- ``Number of the segment to create (segment library)[String]``:
- ``Coefficients for walking energy formula parameters a,b,c,d[String]``:
- ``Lambda coefficients for combining walking energy and friction cost[String]``:
- ``Slope factor determines travel energy cost per height step[String]``:
- ``Use the 'Knight's move'; slower, but more accurate[Boolean]``:
- ``Keep null values in output map[Boolean]``:
- ``Start with values in raster map[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:
- ``v.in.ogr snap tolerance (-1 = no snap)[Number]``:
- ``v.in.ogr min area[Number]``:

Outputs
-------

- ``Output cost layer[Raster]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.walk', elevation, friction, start_points, max_cost, percent_memory, nseg, walk_coeff, lambda, slope_factor, -k, -n, -r, grass_region_parameter, grass_region_cellsize_parameter, grass_snap_tolerance_parameter, grass_min_area_parameter, output)
