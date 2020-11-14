# Project 1) Comparing Numerical Solutions to the Heat Equation

<p align="center">
  <img src="/images/Heat_Equation.png">
</p>

## Summary

**Comparative Analysis of Various Numerical Methods** 

- This project looks at the stability that various numerical methods such as Forward and Backward Euler, and Crank-Nicholson have in modeling the heat equation. Each iteration of each instance of each method is plotted over the time interval so it can easily be seen just how stable each method is.
- The layout of the project is as follows.
  - Establishing the Boundary Value of the Heat Equation that will be used for this analysis
  - Using time step size k = 0.1 and mesh size h = 0.02, perform
  1) forward euler in time and central difference in space
  2) backward euler in time and central difference in space
  3) crank-nicholson in time and central difference in space
  - Repeat these three steps for step sizes k = 0.01, h = 0.02
  - Repeat these three steps for step sizes k = 0.001, h = 0.02
  - Repeat these three steps for step sizes k = 0.0001, h = 0.02

# Project 2) Heat Equation in the Unit Square

<p align="center">
  <img src="/images/Heat_Equation_3D.png">
</p>

## Summary

**Analysis of the Heat Equation in the Unit Square using Peaceman Rachford ADI Method**
- This project demonstrates how the Peaceman-Rachford ADI Method can be used to numerically solve differential equations. The common tool for solving second order ODEs is the Crank-Nicholson Method, however Peaceman-Rachford ADI can improve upon this by leveraging a Tri-Diagonal Matrix solver in order to increase computational speed while preserving accuracy.
- The layout of the project is as follows.
  - Establish the equation that will be used as well as the conditions for the method
  - Plot the three dimensional results of the Heat Equation at three various time steps
  - Run a resolution study to determine if there are any bugs in the project
- The .ipynb file is done in Jupyter Notebook so it was easy to comment in cells between lines of code, as well as write up my thought process as I went along, so the code file itself will serve as a much better guide to the project than the bullet points that summarize it here. So click the link to the code and enjoy.
