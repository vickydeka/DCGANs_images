# Generating Synthetic Images
A Deep Convolutional GAN (DCGAN) is constructed with Keras using Generative Adversarial Networks (GANs) to produce images of fashionable apparel. The Keras Sequential API is used in the following project with Tensorflow 2 as the backend.



In the GAN setup,  we want to be able to sample from a complex, high-dimensional training distribution of the Fashion MNIST images. However, there is no direct way to sample from this distribution. The solution is to sample from a simpler distribution, such as Gaussian noise. We want the model to use the power of neural networks to learn a transformation from the simple distribution directly to the training distribution that we care about. 

