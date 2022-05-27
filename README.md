# IMAGE_SEGMENTATION
This repository offers a comparison study of two image segmentation models: UNET and LINKNET. The image segmentation use case here will be the kaggle-hosted severstal steel defect detection problem.

## DATASET USED:
[Severstal: Steel Defect Detection](https://www.kaggle.com/c/severstal-steel-defect-detection/data)

## PROBLEM STATEMENT: 
The objective of this project is to predict the location and type of deffect found in steel manufacturing using the images provided. for more details you can visit : [Severstal steel](https://www.kaggle.com/c/severstal-steel-defect-detection)<br><br>
curious about Image Segmentaion refer this blogs: 
[image segmentation-1](https://neptune.ai/blog/image-segmentation),
[image_segementaion-2](https://towardsdatascience.com/semantic-image-segmentation-using-fully-convolutional-networks-bf0189fa3eb8)

## EVALUATION MATRIX USED:
The mean Dice coefficient is used to evaluate model . The Dice coefficient compares the pixel-wise agreement between a predicted segmentation and its matching ground truth.<br><br>
refer wiki for more : [DICE COEFFICIENT](https://en.wikipedia.org/wiki/S%C3%B8rensen%E2%80%93Dice_coefficient) 

## MODELS COMPARED:
1. [U-Net](https://arxiv.org/abs/1505.04597):<br> 
U-Net architecture was originally developed for Biomedical Image Segmentation. This architecture mainly contains two paths: Encoder Path & Decoder Path. And the connections between Encoder & Decoder at each level is the key feature of this architecture.<br>
2. [Link-Net](https://arxiv.org/abs/1707.03718):<br>
LinkNet architecture is almost similar to U-Net with a little modification. The Encoder and Decoder path construct remains same as in U-Net. But the outputs of the encoder blocks after passing through the connection gets added(concatenation in case of U-Net ) to the input tensors of the decoder blocks.<br>


## MODEL PREDICTION COMPARED:





## MODEL ACCURACY OBTAINED:
