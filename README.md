# Denoising-Images-with-Autoencoders

DENOISING IMAGES WITH AUTOENCODERS

DATASET :

The dataset used was Olivetti Faces Dataset.
It contains 10 different images of each of 40 distinct subjects.
Hence in total, there were 400 images each of 64x64 dimensions.

ADDING NOISE :

The first step in this problem statement is to add noise to the images.
A random noise using python code was added to all the 400 images.
Data was further split into 320 and 80 images for training and testing respectively. 

SETTING UP THE MODEL:

It is one of the most important steps as denoising would take place here.
I have used Convolutional Autoencoder as CNN has the capability of feature extraction, especially which is very much required here.
Due to relatively small dataset, it gave me the best result at 1000 epochs though I had also tried 100 and 500 epochs.

TESTING THE MODEL:

After we have performed training and testing on our model, it’s was now my turn to check whether the model is performing at par or not.
For this, one would have to predict the noisy test images and compare with the original test images as shown in the code.
As the reconstructed image can be seen, all the features were retained although it was a bit blurred due to its small size.
But overall, a very good job of denoising was accomplished here.
