# Image Clustering

The MNIST digits dataset is a dataset commonly used to demonstrate image recognition. 

The dataset is composed of a set of images of handwritten digits from 0 to 9. There are 1797
images, each 8x8 pixels. If we flatten each image we get a dataset of 1797 observations, each with 64
features, each belonging to one of 10 classes.

In this project we'll see how well these images cluster using KMeans clustering.
We'll compare the KMeans clustering assingments to clusters generated by HAC with Ward linkage.
