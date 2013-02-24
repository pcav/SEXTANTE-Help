R.STATS - GENERATES AREA STATISTICS FOR RASTER LAYERS.
======================================================

Description
-----------

Parameters
----------

- ``Name of input raster map[MultipleInput]``:
- ``Output field separator[String]``:
- ``String representing no data cell value[String]``:
- ``Number of fp subranges to collect stats from[String]``:
- ``One cell (range) per line[Boolean]``:
- ``Print averaged values instead of intervals[Boolean]``:
- ``Print area totals[Boolean]``:
- ``Print cell counts[Boolean]``:
- ``Print APPROXIMATE percents (total percent may not be 100%)[Boolean]``:
- ``Print category labels[Boolean]``:
- ``Print grid coordinates (east and north)[Boolean]``:
- ``Print x and y (column and row)[Boolean]``:
- ``Print raw indexes of fp ranges (fp maps only)[Boolean]``:
- ``Suppress reporting of any NULLs[Boolean]``:
- ``Suppress reporting of NULLs when all values are NULL[Boolean]``:
- ``Report for cats fp ranges (fp maps only)[Boolean]``:
- ``Read fp map as integer (use map's quant rules)[Boolean]``:
- ``GRASS region extent[Extent]``:

Outputs
-------

- ``Output stats file[HTML]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('grass:r.stats', input, fs, nv, nsteps, -1, -a, -a, -c, -p, -l, -g, -x, -r, -n, -n, -c, -i, grass_region_parameter, html)
