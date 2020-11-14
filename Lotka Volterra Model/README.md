# Lotka-Volterra Model

<p align="center">
  <img src="/images/Predator_Prey.png">
</p>

## Summary

**Visualizing Predator Prey Relationships with Cubic Splines**

- The aim of this project is to utilize cubic spline interpolation in order to construct a better way to visualize the predator prey relationship between wolves and moose in Isle Royale. This data was treated as noise free in order to perform this interpolation, and while the second or first derivative were not used on the cubic splines that I created to model this function at any point, the option to calculate them is still an added benefit of the cubic spline technique that cannot be ignored.
- The layout of the project is as follows.
  - Using Fixed Point Iteration determine the steady state of the Lotka-Volterra Equations
  - Build the dozens of cubic splines from scratch that will be used to 'connect the dots' of our data
  - Repeat this process for both predator and prey populations
  - Overlay the graphs to observe the predator prey relationship
- The .ipynb file is done in Jupyter Notebook so it was easy to comment in cells between lines of code, as well as write up my thought process as I went along, so the code file itself will serve as a much better guide to the project than the bullet points that summarize it here. So click the link to the code and enjoy.
