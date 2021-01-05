# Jupyter Notebooks illustrating applications of PDEs:
This repository contains the Jupyter notebooks written in Python that illustrate applications of PDEs:

* **Bacteria model:** dynamics of nonlinear diffusion equations with logistic nonlinearities on bounded intervals with Neumann boundary conditions
* **Brusselator:** stripes and spots that arise via Turing bifurcations in the planar Brusselator model of an autocatalytic chemical reaction (nonlinear diffusion equation on the square with periodic boundary conditions) 
* **Korteweg-de Vries:** explores the dynamics of solitons  and their interactions in the nonlinear KdV equation with periodic boundary conditions
* **Navier-Stokes:** illustrates fluid flow in a planar box with moving lid (adapted from code by Barba group)
* **SIR model:** explores the spreading of infectious diseases in space in a nonlinear heat equation with SIR nonlinearity
* **Stochastic population model:** compares the dynamics of the logistic ODE with multiplicative noise to the stationary solution of the associated Fokker-Planck equation
* **Stochastic wealth distribution model:** compares the dynamics of a stochastic ODE model for the distribution of wealth with stationary solutions of the associated Fokker-Planck equations, and illustrates Pareto indices

These notebooks run on a JupyterLab (which can be installed using, for instance, [Anaconda](https://www.anaconda.com)) with a Python 3 kernel. The notebooks require the modules ipywidgets, math, matplotlib, numpy, and scipy. If IPython is used, replace `%matplotlib widget` with `%matplotlib notebook` in each notebook.
