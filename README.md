# Generalization Error without Independence: Denoising, Linear Regression, and Transfer Learning

The codes are implemented in Python version 3.10.11 using Google Colaboratory. The details about the experiments are provided in the paper and Appendix F. To get started, you can clone the project with 
```
git clone git@github.com:rsonthal/Low-Rank-Generalization-Without-IID.git
```
The jupyter notebooks contain codes for importing required libraries and datasets through PyTorch. The different figures and data can be produced using the notebooks as follows: 

* TransferLearning_GeneralizationError.ipynb
   * In subspace Principal Component Regression Error to generate Figure 1d
   * Out of subspace Principal Component Regression Error for alpha = 0.1 to generate Figure 1h
   * Linear Regression Error to generate figure 3
   * Error for IID test data to generate figure 4
   * Out of subspace Principal Component Regression Error for large alpha to generate Figure 7

* DataAugmentation_GeneralizationError.ipynb
  * Data Augmentation without Independence Results to generate Figure 2d 
  * Data Augmentation without Identicality Results to generate Figure 2h

* OptimalNoise_GeneralizationError.ipynb
  * Optimal Training Noise Results to generate Figure 5
  * Generalization Error using optimal noise to generate Figure 6

* FullDimension_GeneralizationError.ipynb
  * Training data with full dimension results to generate Figure 8

* IIDTraining_GeneralizationError.ipynb
  * IID Training Data Error to generate Figure 9
  * IID Training and Test Data Error to generate Figure 10

