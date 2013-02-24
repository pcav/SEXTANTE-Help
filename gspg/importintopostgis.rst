IMPORT INTO POSTGIS
===================

Description
-----------

Parameters
----------

- ``Layer to import[Vector]``:
- ``Database (connection name)[String]``:
- ``Table to import to[String]``:
- ``Overwrite[Boolean]``:
- ``Create spatial index[Boolean]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('gspg:importintopostgis', input, database, tablename, overwrite, createindex)
