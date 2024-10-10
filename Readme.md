# Rock-Paper-Scissors Image Classification
This project is a machine learning model that classifies images of hand gestures for rock, paper, and scissors.
## Dataset Splitting
The dataset is divided into two parts:
* Training Set (60% of the dataset)
* Validation Set (40% of the dataset)

This split ensures that the model can learn from the training data while being evaluated on the validation set to monitor performance and prevent overfitting.

## Data Augmentation with ImageDataGenerator
To improve the generalization of the model and avoid overfitting, the training images are augmented using the ImageDataGenerator function.

## Model Architecture (Sequential Model)
The model is built using the Sequential API from TensorFlow/Keras. The architecture consists of several convolutional layers followed by max-pooling layers to extract important features from the images, and dense layers for classification. The final layer uses softmax activation to classify the images into three categories: rock, paper, or scissors.

## Model Performance
* Training Accuracy: 96%
* Validation Accuracy: 96%

The model was trained for several epochs, achieving a high accuracy on both the training and validation sets, indicating that it performs well without overfitting. Using Callback which stop the automatic training when the accuracy reaches 96%. 

## Conclusion
This project demonstrates the use of convolutional neural networks (CNN) for image classification, particularly for rock-paper-scissors gestures. Data augmentation and the sequential model approach allowed the model to reach a high accuracy rate of 96%.

