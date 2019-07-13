### Semantic Segmentation

Semantic Segmentation
    - Classifying labels for each pixel, so each pixel is labeled with a class.
    - Grouping together pixels that have similar attributes.
    -

An example of semantic segmentation
![semantic](https://miro.medium.com/max/2000/1*MQCvfEbbA44fiZk5GoDvhA.png)

![semantic2](https://imgur.com/a/hCBBzAE)

Some standard deep networks that have made significant contributions. Often used as the basis of semantic segmentation systems.
- AlexNet (Toronoto)
- VGG-16 (Oxford)
- GoogleNet (Google)
- ResNet (Microsoft)

**Region-Based Semantic Segmentation**
 - R-CNN
 
**Fully Convolutional Network-Based Semantic Segmentation**
    - Learns a mapping from pixels to pixles, without extracting region proposals.
    - In contrast with CNNs which use FC layers, FCNs only have convolutional and pooling layers, making them adaptible to abritrary-sized inputs.
    - Con: Direct predicions are typically low in resolution, resulting in fuzzy boundaries.

**Weakly Supervised Semantic Segmentation**
    - Utilizes annotated bounding boxes for supervision


#### Resources
- https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef
- http://www.cs.toronto.edu/~tingwuwang/semantic_segmentation.pdf
