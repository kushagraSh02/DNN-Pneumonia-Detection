# DNN-Pneumonia-Detection
A DNN made using VGG16 to predict pneumonia in x-ray images.



A Dense Neural Network made using the help of transfer learning to identify whether an image of chest x-ray has pneumonia or not.

Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.

We use a model called 'VGG-16' as a prebuilt model, It is a Convolutional Neural Network (CNN) model proposed by Karen Simonyan and Andrew Zisserman at the University of Oxford. 

The consistent use of 3 x 3 convolutions across the network made the network very simple, elegant, and easy to work with.

We add our layers to the VGG-16 model to use it in our DNN and make a model suitable to classify pneumonia.

We use ImageDataGenerator to allow augmentation with dataset to make dataset emulate diversity as the number of images is not too large.

Dataset URL : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
