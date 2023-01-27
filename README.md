# Photo-recognition-CNN
chest-xray-pneumonia

A convolutional neural network (CNN) is a type of deep learning neural network that is commonly used for image classification. In this project, we will be using a CNN to classify whether a chest X-ray image contains pneumonia or not.

The dataset used for this project contains 5,863 X-ray images of lungs, split into three sets: training, validation, and testing. Each image is labeled as either containing pneumonia or not.

The CNN model was created using the Keras library. The model consists of three convolutional layers and two fully connected layers. We used a dropout of 0.5 to prevent overfitting.

The model was trained for 10 epochs and achieved a accuracy of 87% on the validation set. This is a good result, but there is still room for improvement. Try playing around with the hyperparameters to see if you can get even better results!
