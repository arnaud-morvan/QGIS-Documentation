Check validity
==============

Description
-----------

<put algortithm description here>

Parameters
----------

``Input layer`` [vector: any]
  <put parameter description here>

``Method`` [selection]
  <put parameter description here>

  Options:

  * 0 --- The one selected in digitizing settings
  * 1 --- QGIS
  * 2 --- GEOS

  Default: *0*

Outputs
-------

``Valid output`` [vector]
  <put output description here>

``Invalid output`` [vector]
  <put output description here>

``Error output`` [vector]
  <put output description here>

Console usage
-------------

::

  processing.runalg('qgis:checkvalidity', input_layer, method, valid_output, invalid_output, error_output)

See also
--------

