# Numerical-Analysis
This repository contains numerical analysis projects that cover a variety of topics and is meant to explore both traditional as well as non-traditional numerical methods in a creative manner.

<p align="center">
  <img src="/images/Numerical_Analysis.png">
</p>

## Table of Contents

1. **Testing the Gaussian Process for Numerical Integration**
- The aim of this project is to determine the integral of a continuous function given only discrete data with noise that is collected at N different steps along the function's interval. A Gaussian Process is used to fit a curve as well as a confidence interval to the data produced from the noisy function, and then the Trapezoidal Rule is used to take the integral of this newly created function, since the curve fitted by the Gaussian Process is discrete. 
2. **Heat Equation Analysis**
- There are two projects contained in this folder. The first aims to explore the various numerical differentiation methods that one can use in order to solve the heat equation, and compares the stability of each method. The second project implements the Peaceman Rachford ADI method from scratch on the heat equation, graphs the results in three dimensions, and performs a Resolution Study in order to check for bugs and verify the accuracy of the method.
3. **Cubic Spline Interpolation on Lotka-Volterra Predator Prey Model**
- The aim of this project is to utilize cubic spline interpolation in order to construct a better way to visualize the predator prey relationship between wolves and moose in Isle Royale. This data was treated as noise free in order to perform this interpolation, and while the second or first derivative were not used on the cubic splines that I created to model this function at any point, the option to calculate them is still an added benefit of the cubic spline technique that cannot be ignored.
