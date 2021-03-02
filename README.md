# Adversarial-attacks-and-defence-mechanisms
Implementation of adversarial attacks and their defense mechanisms


1. The first one is the implementation of Fast Gradient Sign Method (FGSM).The FGSM works by:

-Taking an input image

-Making predictions on the image using a trained CNN

-Computing the loss of the prediction based on the true class label

-Calculating the gradients of the loss with respect to the input image

-Computing the sign of the gradient

-Using the signed gradient to construct the output adversarial image
