# A simple Variational AutoEncoder

This code is to test the VAE algorithm, which is applied to generate data. 

This simple project trains VAEs on the FashionMNIST and MNIST datasets, generating new images. I used these simple images (1 channel, 28x28) to focus on the mathematical part, leaving aside domain complexities.

This code can help you understand the principles of VAEs and some of their interesting characteristics. For instance, it allows you to easily balance the mixture of the loss during training or investigate the impact of the inner layers.

All the code is inside a single notebook. Written using PyTorch.

Credits to:
https://github.com/karpathy/minGPT