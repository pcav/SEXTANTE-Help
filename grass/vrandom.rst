V.RANDOM - RANDOMLY GENERATE A 2D/3D VECTOR POINTS MAP.
=======================================================

Description
-----------

Parameters
----------

- ``Number of points to be created[Number]``:
- ``Minimum z height for 3D output[Number]``:
- ``Maximum z height for 3D output[Number]``:
- ``Column for Z values[String]``:
- ``Use drand48() function instead of rand()[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output layer[Vector]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:v.random', n, zmin, zmax, column, -d, grass_region_parameter, output)
