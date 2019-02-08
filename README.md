# GAN-Face-Generation
[//]: # (Image References)

[image1]: ./images/sample1.png "eg1"
[image2]: ./images/sample2.png "eg2"

Use a DCGAN to generate new images of faces that look as realistic as possible!

# Data

The dataset is [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html), it is made of "celebrity" faces that are mostly white but is more complex than the number datasets (like MNIST or SVHN).

# Network Structure

For discriminator, I used 4 convolutional layers with batch normalization (except the first layer), leaky Relu as activation function and a fully connected layer to the output. For generator, I used a similar structure--just transpose of the discriminator.

# Sample Generated Images

![eg1][image1]

![eg2][image2]