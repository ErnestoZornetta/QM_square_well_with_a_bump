{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {
    "collapsed": false
   },
   "source": [
    "# <span style='font-family:times new roman'>**Plotting the wavefunctions of the infinite square well with a bump without given energy values.**</span>\n",
    "\n",
    "### _Introduction:_\n",
    "\n",
    "Quantum Mechanics \\(QM\\) has a monumental impact on the way we interpret the phenomena around us. QM mathematically interprets how particles interact with each other on a subatomic scale! It treats the properties of these particles \\(position, momentum\\) as being given as a wavefunction, $\\psi$ \\[1:51\\-76\\].  In 1926, Erwin Schrödinger came up with a very famous equation known as the Schrödinger equation \\[2\\]. This equation is at the core of quantum mechanics and describes the behavior of a quantum particle. The equation provides the base for calculating energy levels in a given potential with boundary conditions. These energy levels are quantized \\(can have only a set of discrete values\\) \\[1:81–128\\]. The equation also provides the basis for the change of the probability density over time, the probability density is simply  $|\\psi|^2$ \\[1:51\\-76\\]. The infinite square well is a special case of the Schrödinger equation where a particle is confined to a region of space \\[1: 133–189\\] and is mostly used to introduce the basic principles of quantum mechanics which in turn can then be applied to more complex systems. The potential is equal to 0 within that space, and outside it is infinite; therefore, the particle can not escape and is confined.\n",
    "\n",
    "In this report, the fundamental code will be tested for an infinite well with first, a given energy level and then with no given energy level where a plot $\\psi$ will be the result. This can be done, thanks to the special nature of this well, that the boundary conditions are easily established \\[1:133–189\\]. This will then allow us to plot $\\psi$ . Once all these works, a new layer of complication will be added, of a bump within the well. This bump will be centered and will have a finite, defined potential inside the well, meaning there will be more boundary conditions. The aim of this report is to obtain a plot of $\\psi$  and the probability density with no given energy levels for an infinite well with a bump in the middle.\n",
    "\n",
