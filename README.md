<h3> CNN for Time Series Analysis of Satellite Image Data </h3>
<b> Data Source: Zindi </b> </br>
<b> URL: https://zindi.africa/competitions/cgiar-crop-yield-prediction-challenge </b> </br>
<b> Problem Definition: Create a model for estimating the crop-cut maize yield for fields in East Africa </b> </br>
<b> Problem Type: Regression using image data </b> </br> </br>

This code was used to generate the output for the CGIAR Crop Yield Prediction Challenge. First, for a given crop field, the raw satellite image data set was converted into a C x N x P matrix of histograms (where C denotes the number of channels, N denotes the number of histogram bins, and P denotes the number of time points) in a manner similar to that described by You et al. (2017). Next, a CNN was developed to estimate the crop yield using the 3D histograms as input.

<b> Evaluation Summary </b> </br>
**RMSE: 1.855**

*References*
1. Jiaxuan You, Xiaocheng Li, Melvin Low, David Lobell, and Stefano Ermon. 2017. Deep Gaussian process for crop yield prediction based on remote sensing data. In Proceedings of the Thirty-First AAAI Conference on Artificial Intelligence (AAAI'17). AAAI Press, 4559–4565.
