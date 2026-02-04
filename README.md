# Pneumonia-detection-using-deep_learning
# Overview
This project utilizes deep learning techniques, specifically the cnn and  the VGG16 convolutional neural network, to detect pneumonia from chest X-ray images. The models are trained on a dataset consisting of images labeled as either "normal" or "pneumonia".
 # Model Architecture
The VGG16 model, pre-trained on ImageNet, is employed as the base model. The top layers of VGG16 are adapted to fit the binary classification task of pneumonia detection. The model is fine-tuned by freezing the convolutional base and training only the custom classifier layers.
