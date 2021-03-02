# Adversarial-attacks-and-defence-mechanisms
Implementation of adversarial attacks and their defense mechanisms

1. The first one is the implementation of Fast Gradient Sign Method (FGSM) which is an untargeted adversarial attack.The FGSM works by:<br />
 -Taking an input image<br />
 -Making predictions on the image using a trained CNN<br />
 -Computing the loss of the prediction based on the true class label<br />
 -Calculating the gradients of the loss with respect to the input image<br />
 -Computing the sign of the gradient<br />
 -Using the signed gradient to construct the output adversarial image<br />
