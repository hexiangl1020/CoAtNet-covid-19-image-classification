# CoAtNet-covid-19-image-classification

* Increased testing accuracy by 7% by using CoAtNet model for Covid and pneumonia image classification and solved the problem of overfitting.
* Lessen the burden of Covid diagnostics for medical system by introducing machine learning models for image classification.
* A ResNet model was built as a baseline model, with training accuracy of 0.96 and 0.92 of testing accuracy for 15,000 images. The training accuracy is over 0.99 with only 0.89 testing accuracy when we trained only 3,000 images, which indicates a possible overfitting here.
* A CoAtNet model overcame the problem of overfitting by showing 0.87 training accuracy and 0.85 testing accuracy for only 3,000 images. Since the SageMaker did not support the Tensorflow version we were using, we could not run the whole training data for the CoAtNet model. However the learning curve did not show any sign of overfitting, which indicated a promising result for this model.

* All files are jupytor notebooks, which is in the main folder. 

![](images/resnet_partial.png)

![](images/coatnet_partial.png)
