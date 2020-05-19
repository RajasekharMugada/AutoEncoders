# AutoEncoders
AutoEncoder hands on projects

## 01_autoencoder_basics
Goal : Visually identify the clusters in the data set
* In this example, randomly generated data having 2 clusters is used.
* By adding noise to the original data it becomes 3d datset. In this case it is a bit difficult to visually identify the two clusters
* An autencoder network is built and the encoder section is used to convert the 3d data in to 2d. This 2d data is much easier to analize
 
 ## 02_autoencoder_image_reconstruction
 Goal : reconstruct the image with very less feature data
* Input data set is MNIST with 28x28 images (784 - features)
* Autoencoder is used to reduce the dimenions from 784 to 25 and still able to reconstruct the original image with good accuracy

 ## 03_autoencoder_image_noise_removal
 Goal : Remove noise from input images
* Input data set is MNIST with 28x28 images (784 - features)
* Introduce noise in autoencoder network 
* Autoencoder is used to reduce the dimenions from 784 to 25 and still able to reconstruct the original image without noise with good accuracy
* The output images will be noise free even if the input image is noisy

## 04_autoencoder_data_vis
Goal : Insights from data with large number of features
* In this example food consumption data is given for 4 UK countries and asked to pick a country whose consumption pattern is different from the rest
* Inputdata is for 4 countries with 17 features
* Autoencoder is used to reduce 17 features in to 2 to visualize the data more easily
