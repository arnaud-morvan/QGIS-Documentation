Gradient vectors from direction and length
==========================================

Description
-----------

<put algortithm description here>

Parameters
----------

``Direction`` [raster]
  <put parameter description here>

``Length`` [raster]
  <put parameter description here>

``Step`` [number]
  <put parameter description here>

  Default: *1*

``Size Range Min`` [number]
  <put parameter description here>

  Default: *25.0*

``Size Range Max`` [number]
  <put parameter description here>

  Default: *100.0*

``Aggregation`` [selection]
  <put parameter description here>

  Options:

  * 0 --- [0] nearest neighbour
  * 1 --- [1] mean value

  Default: *0*

``Style`` [selection]
  <put parameter description here>

  Options:

  * 0 --- [0] simple line
  * 1 --- [1] arrow
  * 2 --- [2] arrow (centered to cell)

  Default: *0*

Outputs
-------

``Gradient Vectors`` [vector]
  <put output description here>

Console usage
-------------

::

  processing.runalg('saga:gradientvectorsfromdirectionandlength', dir, len, step, size_min, size_max, aggr, style, vectors)

See also
--------

