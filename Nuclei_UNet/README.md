Hey!!!

This is where I have implemented U-Net model for Semantic Segmentation on Nuclei Dataset.

Dataset - 2018 Data Science Bowl (taken from https://www.kaggle.com)

Dataset Link - https://www.kaggle.com/c/data-science-bowl-2018/data

The goal of Semantic Segmentaion is to label each pixel of an image with a corresponding class  of what is being represented. 

U-Net model is a U-shaped model consist of convolutional neural network and deconvolutional neural network.

U-Net has two phases:

One is contraction which is also called as Encoder where all the feature extraction is done. It is used to downsample an image. 

Second one is expansion which is also called as Decoder which is used to perform up sampling of an image with learnable parameters.
