############
boostsrl API
############

.. currentmodule:: boostsrl

Core Classes
============

These classes form the set of core pieces for describing the data, providing
background knowledge, and learning.

.. autosummary::
   :toctree: generated/
   :template: class.rst

   Database
   Background
   rdn.RDN

Data Sets
=========

.. autosummary::
   :toctree: generated/
   :template: dataset.rst

   example_data

Utilities
=========

Some of these are for behind-the-scenes operations, but tend to
be useful for further development
(`contributions are welcome! <https://github.com/hayesall/boostsrl/blob/master/.github/CONTRIBUTING.md>`_).

.. autosummary::
   :toctree: generated/
   :template: class.rst

   base.BaseBoostedRelationalModel
   system_manager.FileSystem

.. autosummary::
   :toctree: generated/
   :template: function.rst

   system_manager.reset

Deprecated boostsrl objects
===========================

This is the old API style that has been deprecated. It is no longer tested or
actively developed and is pending removal in 0.6.0.

.. autosummary::
   :toctree: generated/

   boostsrl.boostsrl
