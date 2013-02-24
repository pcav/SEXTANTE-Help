CHANGE DATE FORMAT
==================

Description
-----------

Parameters
----------

- ``Table[Table]``:
- ``Date Field[TableField]``:
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

	sextante.runalg('saga:changedateformat', table, field, fmt_in, fmt_out, output)

	Available options for selection parameters:

	fmt_in(Input Format)
		0 - [0] dd.mm.yy
		1 - [1] yy.mm.dd
		2 - [2] dd:mm:yy
		3 - [3] yy:mm:dd
		4 - [4] ddmmyyyy, fix size
		5 - [5] yyyymmdd, fix size
		6 - [6] ddmmyy, fix size
		7 - [7] yymmdd, fix size
		8 - [8] Julian Day

	fmt_out(Output Format)
		0 - [0] dd.mm.yy
		1 - [1] yy.mm.dd
		2 - [2] dd:mm:yy
		3 - [3] yy:mm:dd
		4 - [4] ddmmyyyy, fix size
		5 - [5] yyyymmdd, fix size
		6 - [6] ddmmyy, fix size
		7 - [7] yymmdd, fix size
		8 - [8] Julian Day
