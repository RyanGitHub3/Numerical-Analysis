# Gaussian_Process

<p align="center">
  <img src="/images/Gaussian_Process.png">
</p>

## Summary

**Building a Gaussian Process From Scratch & Analyzing its Numerical Integration Capabilities**

- This project constructs a Gaussian Process from scratch (not using the built in Gaussian Process algorithm in the sklearn library) in order to fit a curve and interval to a noisy data set. The aim of fitting this curve is to best approximate the function that the noisy data was produced from. The discretized points that make up the Gaussian Process curve are then used in combination with the Trapezoidal Rule in order to integrate the function. Lastly this integral is compared to the utilizing the Trapezoidal Rule on the true function as well as on the noisy data in order to see the accuracy of using GP for numerical integration.
- The layout of the project is as follows.
  - Constructing an arbitrary function and noisy dataset to model
  - Building the Gaussian Process from scratch by making the kernel
  - Optimizing the Hyperparameters of the Gaussian Process
  - Plotting the curve/interval that the Gaussian Process has fit to the dataset
    and comparing it to the true curve graphically
  - Using the curve generated from the Gaussian Process in combination with the Trapezoidal Rule
    perform numerical integration and compare the results to using the Trapezoidal Rule on the noisy data
    as well as on the true function
- The .ipynb file is done in Jupyter Notebook so it was easy to comment in cells between lines of code, as well as write up my thought process as I went along, so the code file itself will serve as a much better guide to the project than the bullet points that summarize it here. So click the link to the code and enjoy.
