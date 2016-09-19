Introduction to eZND
====================

The eZND code solves for steady-state detonations where post-shock expansion is important in determining the structure of the detonation. It is a 1D code, and therefore relies on adequate parametrization of the various multidimensional expansive effects as a function of distance behind the shock front. 

It was written to compute the structure of surface helium detonations on accreting white dwarfs, presented in this `paper <http://adsabs.harvard.edu/abs/2013arXiv1308.4193M>`_. It also contains solvers for other auxiliary detonation properties (eg. CJ solutions, standard ZND structure, hydrostatic white dwarfs).

eZND uses `MESA <http://mesa.sourceforge.net>`_ for its microphysics (equations of state, reaction networks, integrators, etc.) so you must have MESA installed on your system. For this reason, the code was written in Fortran and tested primarily with the build environment provided by the `MESA SDK <http://www.astro.wisc.edu/~townsend/static.php?ref=mesasdk>`_.