CHANGE TIME FORMAT
==================

Description
-----------

Parameters
----------

- ``Table[Table]``:
- ``Time Field[TableField]``:
- ``Input Format[Selection]``:
- ``Output Format[Selection]``:

Outputs
-------

- ``Output[Table]``:

See also
---------


Console usage
-------------


::

	sextante.runalg('saga:changetimeformat', table, field, fmt_in, fmt_out, output)

	Available options for selection parameters:

	fmt_in(Input Format)
		0 - [0] hh.mm.ss
		1 - [1] hh:mm:ss
		2 - [2] hhmmss, fix size
		3 - [3] hours
		4 - [4] minutes
		5 - [5] seconds

	fmt_out(Output Format)
		0 - [0] hh.mm.ss
		1 - [1] hh:mm:ss
		2 - [2] hhmmss, fix size
		3 - [3] hours
		4 - [4] minutes
		5 - [5] seconds
