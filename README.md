# Face Detection with MTCNN and Face Recognition with CNN & Transfer Learning via VGG19

This repository focuses on implementation of various neural network architecture on face recognition such as CNN and pre-build model such as VGG19.

## Folder Structure
- Models: All the models are saved in this folder with their weights.
- face_detection: All the images after face detection are stored.
- face_detection_output: All the images after face detection, but seperated into train,valid,test folders.
- sample: Store sample images
- Face Recognition using CNN.ipynb: Code for face recognition
- Face Recognition with Face Detection.ipynb: Code for face detection


## Dataset

The dataset is available in [kaggle free dataset](https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset). Due to limitation of size of repo, the images are saved in my own google drive. The dataset used in this project comprises of 29 different celebrities. Here we aim to use classification method to solve face recognition problem.

The sample data is at below:

## Pre-processing using MTCNN

Pre-processing (face detection) is done to reduce the background noise of the data. This is to improve the accuracy of our final model when it comes to face recognition.
This is done in [face detection using cnn notebook](https://github.com/Wayne1202/transfer-learning-face-recognition/blob/main/Face%20Recognition%20with%20Face%20Detection.ipynb). 
The sample output after the face detection would be:


## Face Recognition

In this [notebook](https://github.com/Wayne1202/transfer-learning-face-recognition/blob/main/Face%20Recognition%20using%20CNN.ipynb), we have implemented both CNN and EfficientNet as our model in face recognition tasks. Certainly, various different deep neural network models have been tried out and EfficientNet has the best accuracy among them.

## Result

CNN
> train_accuracy = 99%
> valid_accuracy = 72%
> test_accuracy = 72%

VGG19
> train_accuracy = 9%
> valid_accuracy = 10%
> test_accuracy = 9%

## Future Improvements
- Improve performance of VGG19
- Add regularisation, improve test accuracy.
- Implement Siamese Network.



