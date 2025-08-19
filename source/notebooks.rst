Jupyter Notebooks
=====================================================================================

Class notes will be written in [Jupyter Notebooks](https://jupyter.org) and [Julia](https://julialang.org).
Use the command

.. code-block:: console

   julia -e 'import Pkg; Pkg.add("IJulia")'


in your terminal to enable Julia in Jupyter.
You may need to add other packages in the same fashion when attempting to run a cell with a `using` statement, such as

.. code-block:: julia

   using Polynomials

So you would first run the command

.. code-block:: console

   julia -e 'import Pkg; Pkg.add("Polynomials")'

before you can run cells that use the ``Polynomials`` package.

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   notebooks/2025-08-22-Welcome.ipynb

