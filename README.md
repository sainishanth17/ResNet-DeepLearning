# ModifiedResNets-DL-NYU
This repository contains our code for the Deep Learning project as part of the coursework of NYU. Where in we are working with modified residual network (ResNet) architecture to get the highest test accuracy on the CIFAR- 10 image classification dataset.

### Introduction:
In this project, we aimed to achieve high test accuracy on the CIFAR-10 image classification dataset using a modified ResNet architecture, while keeping the number of parameters under 5 million. We experimented with various architectural choices, optimizers, data augmentation techniques, and regularization methods. Our final model achieved a test accuracy of 93.55%, demonstrating the effectiveness of our modifications.

CIFAR-10 is a popular dataset used for evaluating image classification models, consisting of 60,000 32x32 images in 10 classes. ResNet is a well-known deep residual network architecture, which leverages skip connections to improve gradient flow and enable deeper models. In this project, we designed and trained a modified ResNet architecture to classify CIFAR-10 images with high accuracy while maintaining a constraint on the number of parameters.

We've experimented with tuning in various hyperparameters, more detials about which are mentioned in the Project Report.

### Running Model 3 using cutout regularization:
In order to run the code for Model 3, we need to add/upload the cutout.py file to our runtime environment. This is done to introduce cutout Regularization. The rest of the hyperparameters remain the same as Model 2.
