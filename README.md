# Image-Segmentation
This repository offers a comparison study of three image segmentation models: UNET, LINKNET, and UNET++. The image segmentation use case here will be the kaggle-hosted severstal steel defect detection problem.

## Dataset:
[Severstal: Steel Defect Detection](https://www.kaggle.com/c/severstal-steel-defect-detection/data)

## Problem Statement: 
The objective of this project is to predict the location and type of deffect found in steel manufacturing using the images provided. for more details you can visit : [Severstal steel](https://www.kaggle.com/c/severstal-steel-defect-detection)<br>
curious about Image Segmentaion refer this blogs: 
[image segmentation-1](https://neptune.ai/blog/image-segmentation),
[image_segementaion-2](https://towardsdatascience.com/semantic-image-segmentation-using-fully-convolutional-networks-bf0189fa3eb8)

## Evaluation Matrix used:
The mean Dice coefficient is used to evaluate model . The Dice coefficient compares the pixel-wise agreement between a predicted segmentation and its matching ground truth.The formula is given by:
{\displaystyle DSC={\frac {2|X\cap Y|}{|X|+|Y|}}}


refer wiki for more : [DICE COEFFICIENT](https://en.wikipedia.org/wiki/S%C3%B8rensen%E2%80%93Dice_coefficient) 
