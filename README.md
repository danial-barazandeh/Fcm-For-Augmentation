# FCM Augmentation

This project was created to test if we could use FCM to generate more data in a dataset to improve accuracy. In this case, FCM is used as an augmentation method.

## cluster.ipynb

This script process images into 6 clusters with FCM.

## Mobilenet_Mix_Binary_cluster.ipynb

This script trains and tests Mobilenet with clustered images.

## Mobilenet_Simple_Binary.ipynb

This script trains and tests Mobilenet without clustered images.

### Dataset

The dataset folder contains the dataset booth processed with FCM and without it. 

### Model

The model folder contains the trained models. One of them is trained with FCM data. The other is not. 

# Goal

Our goal is to prove FCM could be used to augment training data to get better accuracy with fewer data in our dataset.
