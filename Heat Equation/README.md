# Numerical Analysis of the Heat Equation

## Heat Equation in the Unit Square
<p align="center">
  <img src="/images/Heat_Equation_3D.png">
</p>

This project demonstrates how the Peaceman-Rachford ADI Method can be used to numerically solve differential equations. The common tool for solving second order ODEs is the Crank-Nicholson Method, however Peaceman-Rachford ADI can improve upon this by leveraging a Tri-Diagonal Matrix solver in order to increase computational speed while preserving accuracy.

## Comparing Numerical Solutions to the Heat Equation
<p align="center">
  <img src="/images/Heat_Equation.png">
</p>

This project looks at the stability that various numerical methods such as Forward and Backward Euler, and Crank-Nicholson have in modeling the heat equation. Each iteration of each instance of each method is plotted over the time interval so it can easily be seen just how stable each method is.
