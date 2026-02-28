aircond: an example for optimization under uncertainty
======================================================

This repository contains documentation and archived source code for the
``aircond`` family of scalable stochastic programming test instances used
with `mpi-sppy <https://github.com/Pyomo/mpi-sppy>`_.

Models
------

- **aircond** (``aircond.pdf``): The original single-product, multi-stage
  production planning model with overtime production, inventory
  carry-forward, and optional start-up costs.

- **aircondMulti** (``aircondMulti.pdf``): A multi-product extension
  where *P* products share a common regular-time capacity while
  maintaining independent demand streams, inventories, and overtime
  production.  Includes support for mpi-sppy bundling.

Archives of the corresponding Python modules are in the ``archives/``
directory.
