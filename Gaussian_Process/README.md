# Gaussian Process

<p align="center">
  <img src="/images/Gaussian_Process.png">
</p>

This project constructs a Gaussian Process from scratch (not using the built in Gaussian Process algorithm in the sklearn library) in order to fit a curve and interval to a noisy data set. The aim of fitting this curve is to best approximate the function that the noisy data was produced from. The discretized points that make up the Gaussian Process curve are then used in combination with the Trapezoidal Rule in order to integrate the function. Lastly this integral is compared to the utilizing the Trapezoidal Rule on the true function as well as on the noisy data in order to see the accuracy of using GP for numerical integration.
