# Sketch2Color-Anime-Translation-with-UNet

## Problem Statement:
For a given sketch generate a Color Image.

## Dataset: https://www.kaggle.com/wuhecong/danbooru-sketch-pair-128x

## U-Net Model
The U-Net model architecture is very similar to encoder decoder model that it involves downsampling to a bottleneck and upsampling again to an output image, but links or skip-connections are made between layers of the same size in the encoder and the decoder, allowing the bottleneck to be circumvented.

![](https://cdn-images-1.medium.com/max/800/1*ESSseolApYaDVQ9w-48l9A.png)

