==============
Darcy Analytic
==============

Darcy's law is an equation that describes the flow of a fluid through a porous medium.
The analytic solution of the Darcy equation is implemented in this example.


Building the example
====================

The fortran version of the example can be configured and built with CMake::

  git clone https://github.com/OpenCMISS-Examples/darcy_analytic.git
  mkdir darcy_analytic-build
  cd darcy_analytic-build
  cmake -DOpenCMISSLibs_DIR=~/opencmiss/install/  ../darcy_analytic/
  make


Running the example
===================

Fortran version::

  cd src/fortran/
  ./darcy_analytic_fortran

The results can be visualised by running `visualise.com <./src/fortran/visualise.com>`_ with the `Cmgui visualiser <http://physiomeproject.org/software/opencmiss/cmgui/download>`_.


Prerequisites
=============

There are no additional input files required for this example as it is self-contained.


License
=======

License applicable to this example is described in `LICENSE <./LICENSE>`_.
