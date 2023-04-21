# Image-Classification
Pretrained CNN models in Keras-tensorflow environment

The goal of the project is to build an Artificial Neural Network that recognizes objects. For this a database is created that includes three class of images (bottle, flask & lunchbox) captured through webcam. Each class containing 100 images for training the model. For classification purpose Keras with tensorflow package is used. This project could act as a base for including more classes, further optimizing hyperparameters, etc in the future. Following things are done to achieve the aim of the project.
+	Data pre-processing and creating training and validation data.
+	Use LeNet-5 architecture, check the loss and accuracy and finally predict an unseen image.
+ Load pretrained MobileNet CNN architecture and predict the unseen image.
+	Finally, use the same pretrained MobileNet architecture as base model, include the three new classes, add dense hidden layer, tune hyperparameters, etc. Compile and fit the model, check the prediction and validation loss and finally predict few images.
+	ResNet-50 architecture is also used, same like MobileNet architecture, just for comparison.
+	Save the model for future use and identify limitations of the project.
