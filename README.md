# Autoencoder
## Model
This GitHub repository features a comprehensive PyTorch implementation of two types of autoencoders: a linear autoencoder and a convolutional autoencoder, both aimed at compressing and reconstructing MNIST digit images. The linear autoencoder (`Autoencoder_Linear`) reduces the dimensionality of the input images using fully connected layers, while the convolutional autoencoder (`Autoencoder_CNN`) leverages convolutional layers for the same purpose.



![Autoencoder](https://github.com/zahraasadi257/Autoencoder/assets/57061013/1cd8bc53-7556-4f5a-872f-e1c0ef8d764e)











Both models are trained using the Mean Squared Error (MSE) loss to minimize the reconstruction error. The training loop iterates over the MNIST dataset, feeding batches of images through the autoencoders and updating the model parameters to improve reconstruction quality.
## Results
The repository also includes visualization code to display original and reconstructed images side by side, allowing for a visual assessment of the autoencoder's performance. The code is well-documented, making it easy for others to understand and replicate the experiments.








![MNIST](https://github.com/zahraasadi257/Autoencoder/assets/57061013/ea8931fe-31fd-4f73-97a9-4faef59df8d3)







![MNIST2](https://github.com/zahraasadi257/Autoencoder/assets/57061013/dab98daa-dd1c-4100-bc7c-e5da49350d3e)






![MNIST3](https://github.com/zahraasadi257/Autoencoder/assets/57061013/efc7ec02-c5f4-4d2c-ab3b-b6de8324daea)





