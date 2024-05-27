This GitHub repository features a comprehensive PyTorch implementation of two types of autoencoders: a linear autoencoder and a convolutional autoencoder, both aimed at compressing and reconstructing MNIST digit images. The linear autoencoder (`Autoencoder_Linear`) reduces the dimensionality of the input images using fully connected layers, while the convolutional autoencoder (`Autoencoder_CNN`) leverages convolutional layers for the same purpose.






Both models are trained using the Mean Squared Error (MSE) loss to minimize the reconstruction error. The training loop iterates over the MNIST dataset, feeding batches of images through the autoencoders and updating the model parameters to improve reconstruction quality
