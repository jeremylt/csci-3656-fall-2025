Jupyter Notebooks
=====================================================================================

Class notes will be written in `Jupyter Notebooks <https://jupyter.org>`_ and `Julia <https://julialang.org>`_.
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

Introduction
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-08-22-Welcome.ipynb
   notebooks/2025-08-25-Functions.ipynb
   notebooks/2025-08-27-Function-Error.ipynb
   notebooks/2025-08-29-Conditioning.ipynb

Rootfinding
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-09-03-Rootfinding.ipynb
   notebooks/2025-09-05-Convergence-Classes.ipynb
   notebooks/2025-09-08-Newton-Methods.ipynb
   notebooks/2025-09-10-More-Newton.ipynb
   notebooks/2025-09-12-Formulation.ipynb
   notebooks/2025-09-15-Stability.ipynb

Linear algebra
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-09-17-Linear-Algebra.ipynb

