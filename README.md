# Fork
-------------------

Forked from https://github.com/m4jidRafiei/Decision-Tree-Python-

## Modifications
--------------------

* `print_visualTree` now accepts a `render=bool` attribute to avoid automatic rendering.
* `print_visualTree` now returns the Digraph and allows modification and manual rendering.
* Recursive id3 step now passes a copy of attributes to each sibling.
* Digraph node ids are now randomly generated instead of using the node value.
