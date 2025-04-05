# ASSIGNMENT3--Q2
Implementing a Denoising Autoencoder
Name: Sony Pailla

Course: CS5720 Neural Network and Deep Learning (Spring 2025)

University: University of Central Missouri

GitHub: sonypailla
The MNIST dataset (handwritten digits) is used for training the autoencoder. It consists of grayscale images of size 28x28 pixels representing digits from 0 to 9.
1. Import Libraries and Load Dataset
The MNIST dataset is loaded and normalized to values between 0 and 1.
2. Add Gaussian Noise (Denoising Autoencoder)
We add Gaussian noise to the images with a mean of 0 and standard deviation of 0.5.
3. Build the Denoising Autoencoder Model
The autoencoder consists of an encoder to compress the image and a decoder to reconstruct the image.
4. Train the Model
We train the denoising autoencoder to reconstruct clean images from the noisy images.
5. Visualize Noisy vs. Reconstructed Images
After training, we visualize the noisy images and their reconstructed counterparts.
6. Compare Performance with Basic Autoencoder
We can compare the performance of a basic autoencoder (without added noise) by training and visualizing its reconstruction.
Real-World Application: Denoising Autoencoders in Medical Imaging
Denoising autoencoders can be used in medical imaging to improve the quality of MRI scans, CT scans, and X-rays. Medical images are often noisy due to factors like low-quality scanners or motion artifacts. Denoising autoencoders can remove the noise and reconstruct the clean image, which aids in better diagnosis.
