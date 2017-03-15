# Deep Learning Nanodegree Foundations -- Project 2

Build and train convolutional neural network to classify images from the CIFAR-10 dataset.

## Notes
1. normalize function can probably be done without min/max. We're dealing with pixels, so min is always 0 and max is always 255.
1. custom fully_connected/flatten/output functions were swapped out for tf.contrib functions -- custom implementations were likely faulty because learning rate never went past 42%
1. bias is zero and weights initialized using trancate normal with stddev set to 0.05 -- we do this because in the lecture they stated that higher initial weights mean the convnet is in a more "certain" state and as such has a harder time learning.