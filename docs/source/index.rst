Welcome to |name|'s documentation!
==================================

.. image:: _static/images/logo/logo.svg
   :width: 175 px
   :alt: Logo
   :align: right

|name_bold| (|name_long|) is a modular framework for partitioned aeroelastic analyses. The framework couples separate solvers for structure and CFD_. It coordinates the analysis and the exchange of loads and deformations. Currently, |name| supports *static* aeroelastic analyses.

.. figure:: _static/images/cover_img.png
   :width: 400 px
   :alt: Cover
   :align: center

   Wing deformations in a pull-up maneuver. Aerodynamics computed with the vortex-lattice method (VLM) and the structural repsonse with a beam FEM_ model (image from [Dett19]_).

.. toctree::
   :maxdepth: 1
   :caption: User guide

   user_guide/installation
   user_guide/detailed_user_guide
   user_guide/tool_prerequisites
   user_guide/conventions
   user_guide/wrappers
   user_guide/tutorials
   user_guide/limitations

.. toctree::
   :maxdepth: 2
   :caption: Theory

   theory/index
   theory/coupling
   theory/beam_models

.. toctree::
   :maxdepth: 1
   :caption: Links

   references
   related_projects

.. toctree::
   :maxdepth: 1
   :caption: Changelog

   CHANGELOG.md

.. toctree::
   :maxdepth: 1
   :caption: Contributing

   contribute/index

.. toctree::
   :maxdepth: 1
   :caption: Developer documentation

   dev_doc/index
   dev_doc/modules_main


Licence information
-------------------

|name| is developed at `Airinnova AB`_, Stockholm.

:Author:
    |author1|

:Licence:
    |license|
