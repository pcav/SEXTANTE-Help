R.TERRAFLOW - FLOW COMPUTATION FOR MASSIVE GRIDS (FLOAT VERSION).
=================================================================

Description
-----------

Parameters
----------

- ``Name of elevation raster map[Raster]``:
- ``SFD (D8) flow (default is MFD)[Boolean]``:
- ``GRASS region extent[Extent]``:
- ``GRASS region cellsize (leave 0 for default)[Number]``:

Outputs
-------

- ``Name for output filled (flooded) elevation raster map[Raster]``:
- ``Name for output flow direction raster map[Raster]``:
- ``Name for output sink-watershed raster map[Raster]``:
- ``Name for output flow accumulation raster map[Raster]``:
- ``Name for output topographic convergence index (tci) raster map[Raster]``:
- ``Name of file containing runtime statistics[File]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.terraflow', elevation, -s, grass_region_parameter, grass_region_cellsize_parameter, filled, direction, swatershed, accumulation, tci, stats)
