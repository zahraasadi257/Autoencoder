# Autoencoder
## Model
This GitHub repository features a comprehensive PyTorch implementation of two types of autoencoders: a linear autoencoder and a convolutional autoencoder, both aimed at compressing and reconstructing MNIST digit images. The linear autoencoder (`Autoencoder_Linear`) reduces the dimensionality of the input images using fully connected layers, while the convolutional autoencoder (`Autoencoder_CNN`) leverages convolutional layers for the same purpose.



![Autoencoder](https://github.com/zahraasadi257/Autoencoder/assets/57061013/1cd8bc53-7556-4f5a-872f-e1c0ef8d764e)









Both models are trained using the Mean Squared Error (MSE) loss to minimize the reconstruction error. The training loop iterates over the MNIST dataset, feeding batches of images through the autoencoders and updating the model parameters to improve reconstruction quality.
## Results
The repository also includes visualization code to display original and reconstructed images side by side, allowing for a visual assessment of the autoencoder's performance. The code is well-documented, making it easy for others to understand and replicate the experiments.
