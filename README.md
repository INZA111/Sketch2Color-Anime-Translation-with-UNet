# Sketch2Color-Anime-Translation-with-UNet

### Problem Statement:
For a given sketch generate a Color Image.

### Dataset: https://www.kaggle.com/wuhecong/danbooru-sketch-pair-128x
### Blog: https://khaninza.medium.com/sketch2color-anime-translation-with-u-net-2efaff6d8090

### U-Net Model
The U-Net model architecture is very similar to encoder decoder model that it involves downsampling to a bottleneck and upsampling again to an output image, but links or skip-connections are made between layers of the same size in the encoder and the decoder, allowing the bottleneck to be circumvented.

![](https://cdn-images-1.medium.com/max/800/1*ESSseolApYaDVQ9w-48l9A.png)

### Training Loss Vs Validation Loss
![](https://cdn-images-1.medium.com/max/800/1*dcfwkmHrHk1IZlL5QSLMzQ.png)

### In progress Training results:

#### At epoch 0
![](https://cdn-images-1.medium.com/max/800/1*lHGG5DaQysmwzAAWtwMEjQ.png)

#### At epoch 20
![](https://cdn-images-1.medium.com/max/800/1*6Ih3B1J777FDXc92IQz05A.png)

#### At epoch 60
![](https://cdn-images-1.medium.com/max/800/1*aG1_Q1ibJuaboLxy0phwag.png)

### Prediction on test sketches:
![](https://cdn-images-1.medium.com/max/800/1*__uhB5Tb0IzSHfxCVR-CJQ.png)

### Conclusion:
Model performed well on unseen images.

