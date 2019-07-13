### Semantic Segmentation


- Classifying labels for each pixel, so each pixel is labeled with a class.
- Grouping together pixels that have similar attributes.
   
**Examples of segmentation**
![](https://i.imgur.com/43VZ1wr.png)

![semantic](https://miro.medium.com/max/2000/1*MQCvfEbbA44fiZk5GoDvhA.png)

![semantic2](https://i.imgur.com/B7u8Rwz.png)

**Some standard deep networks that have made significant contributions. Often used as the basis of semantic segmentation systems.**

- [AlexNet (Toronto)](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
- [VGG-16 (Oxford)](https://arxiv.org/pdf/1409.1556.pdf)
- [GoogleNet (Google)](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf)
- [ResNet (Microsoft)](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Region-Based Semantic Segmentation**
 - Using pixel values to segment different objects by using a threshold value. (Threshold segmentation) 

**Fully Convolutional Network-Based Semantic Segmentation**
- Learns a mapping from pixels to pixles, without extracting region proposals.
- In contrast with CNNs which use FC layers, FCNs only have convolutional and pooling layers, making them adaptable to arbitrary sized inputs.
 - Con: Direct predicions are typically low in resolution, resulting in fuzzy boundaries.
    
![fcn](https://i.imgur.com/RtYkQft.png)

**Weakly Supervised Semantic Segmentation**
 - Utilizes annotated bounding boxes for supervision

**Segmentation based on Clustering**
- Divides the pixels of the image into homogenous clusters.

**Mask R-CNN**
- Class, bounding box, and object mask


#### Resources
- [http://www.cs.toronto.edu/~tingwuwang/semantic_segmentation.pdf](http://www.cs.toronto.edu/~tingwuwang/semantic_segmentation.pdf)
- [https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef](https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef)
- [https://www.analyticsvidhya.com/blog/2019/04/introduction-image-segmentation-techniques-python/](https://www.analyticsvidhya.com/blog/2019/04/introduction-image-segmentation-techniques-python/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NDk3Nzk1MTgsMjAxMzQzMTU5MywtOD
Y3NjgyNzUzLC0xMjU5OTMxMjQ4XX0=
-->