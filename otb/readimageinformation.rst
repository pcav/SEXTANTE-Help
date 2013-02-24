READ IMAGE INFORMATION
======================

Description
-----------

Parameters
----------

- ``Input Image[Raster]``:
- ``Display the OSSIM keywordlist[Boolean]``:
- ``Size X[Number]``:
- ``Size Y[Number]``:
- ``Pixel Size X[Number]``:
- ``Pixel Size Y[Number]``:
- ``Image Origin X[Number]``:
- ``Image Origin Y[Number]``:
- ``Estimated ground spacing X[Number]``:
- ``Estimated ground spacing Y[Number]``:
- ``Number Of Bands[Number]``:
- ``Sensor id[String]``:
- ``Image id[String]``:
- ``Acquisition time[String]``:
- ``Upper left lattitude[Number]``:
- ``Upper left longitude[Number]``:
- ``Upper right lattitude[Number]``:
- ``Upper right longitude[Number]``:
- ``Lower right lattitude[Number]``:
- ``Lower right longitude[Number]``:
- ``Lower left lattitude[Number]``:
- ``Lower left longitude[Number]``:
- ``Nearest town[String]``:
- ``Country[String]``:
- ``Red Band[Number]``:
- ``Green Band[Number]``:
- ``Blue Band[Number]``:
- ``Projection[String]``:
- ``Keywordlist[String]``:
- ``GCPs Number[Number]``:
- ``GCP Projection[String]``:

Outputs
-------


See also
---------


Console usage
-------------


::

	sextante.runalg('otb:readimageinformation', -in, -keywordlist, -sizex, -sizey, -spacingx, -spacingy, -originx, -originy, -estimatedgroundspacingx, -estimatedgroundspacingy, -numberbands, -sensor, -id, -time, -ullat, -ullon, -urlat, -urlon, -lrlat, -lrlon, -lllat, -lllon, -town, -country, -rgb.r, -rgb.g, -rgb.b, -projectionref, -keyword, -gcp.count, -gcp.proj)
