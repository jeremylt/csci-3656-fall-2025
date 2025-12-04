Class Notes
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

Linear Algebra
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-09-17-Linear-Algebra.ipynb
   notebooks/2025-09-19-Geometry.ipynb
   notebooks/2025-09-22-Gram-Schmidt.ipynb
   notebooks/2025-09-24-QR-Factorization.ipynb
   notebooks/2025-09-26-QR-Stability.ipynb
   notebooks/2025-09-29-Householder-QR.ipynb
   notebooks/2025-10-01-QR-Retrospective.ipynb
   notebooks/2025-10-03-Singular-Value-Decomposition.ipynb
   notebooks/2025-10-06-SVD-Geometry.ipynb
   notebooks/2025-10-08-Low-Rank.ipynb

Interpolation
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-10-10-Polynomial-Interpolation.ipynb
   notebooks/2025-10-13-Global-and-Piecewise-Interpolation.ipynb
   notebooks/2025-10-15-Spline-Interpolation.ipynb
   notebooks/2025-10-17-Higher-Dimensions.ipynb
   notebooks/2025-10-20-Noisy-Data.ipynb
   notebooks/2025-10-22-Regression.ipynb
   notebooks/2025-10-24-Beyond-Linear.ipynb
   notebooks/2025-10-27-Gradient-Descent.ipynb
   notebooks/2025-10-29-Nonlinear-Regression.ipynb

Derivatives and Integrals
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-10-31-Differentiation.ipynb
   notebooks/2025-11-03-Optimization.ipynb
   notebooks/2025-11-05-Integration.ipynb
   notebooks/2025-11-07-Quadrature.ipynb
   notebooks/2025-11-10-Transformed-Quadrature.ipynb
   notebooks/2025-11-12-Differential-Equations.ipynb
   notebooks/2025-11-14-Stiff-Equations.ipynb

Applications
-------------------------------------------------------------------------------------

.. toctree::
   :maxdepth: 1

   notebooks/2025-11-17-ODE.ipynb
   notebooks/2025-11-19-PDE.ipynb
   notebooks/2025-11-21-PDE-2D.ipynb

