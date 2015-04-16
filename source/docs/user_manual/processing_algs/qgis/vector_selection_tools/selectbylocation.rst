Select by location
==================

Description
-----------

<put algortithm description here>

Parameters
----------

``Layer to select from`` [vector: any]
  <put parameter description here>

``Additional layer (intersection layer)`` [vector: any]
  <put parameter description here>

``Geometric predicate`` [geometrypredicate]
  <put parameter description here>

  Default: *[]*

``Modify current selection by`` [selection]
  <put parameter description here>

  Options:

  * 0 --- creating new selection
  * 1 --- adding to current selection
  * 2 --- removing from current selection

  Default: *0*

Outputs
-------

``Selection`` [vector]
  <put output description here>

Console usage
-------------

::

  processing.runalg('qgis:selectbylocation', input, intersect, predicate, method)

See also
--------

