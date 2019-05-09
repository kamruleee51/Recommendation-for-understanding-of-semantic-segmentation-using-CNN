# Understanding-of-semantic-segmentation-using-CNN

In general, CNN for the semantic segmentation consists of two essential parts for the pixel wise classification to assign the pixel labels. The first part is encoder composed of convolutional which is responsible for the automatic features extraction and sub-sampling layers. The purpose of the sub-sampling layers is to achieve spatial in-variance by reducing the resolution of the feature maps which also improves the robustness of the classifier due to elimination of the redundant features. Sub-sampling also increases the field of view of the feature maps to extract more abstract class salient features and  minimizes computation time. Sometimes, dropout layer or batch normalization or even both are added after each convolution to avoid the overfitting and to make the robust pixel wise classifier. On the other hand, second part is decoder to semantically project the discriminating features of lower resolution learnt by the encoder onto the pixel space of higher resolution to get a dense pixel wise classification. In semantic segmentation, the encoder part is quite similar to all the CNN models but they mainly differ in decoder mechanism. Semantic segmentation not only requires discrimination at pixel level but also a decoder mechanism to project the discriminating features learnt at different stages of the encoder onto the pixel space. However, the significantly reduced features map due to sub-sampling, suffers spatial resolution loss which introduce coarseness, less edge information, checkerboard noise and over-segmentation in semantically segmented image. When the kernel size of the deconvolution is not divisible by the up-scaling factor, the number of low resolution features that contribute to a single high resolution feature is not constant across the high resolution feature maps which is called deconvolution overlap and is one of the cause of checkerboard artifact in segmented mask.

## Useful links for understanding semantic segmentation 
- [x] Title: How to do Semantic Segmentation using Deep learning <br>
      Link : https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef
      
- [x] Title: How to do Semantic Segmentation using Deep learning <br>
      Link : https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef     
      
- [x] Title: How to do Semantic Segmentation using Deep learning <br>
      Link : https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef

- [x] Title: How to do Semantic Segmentation using Deep learning <br>
      Link : https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef
      
      
- [x] Title: How to do Semantic Segmentation using Deep learning <br>
      Link : https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef


#### Written by-
#### Md. Kamrul Hasan 
#### Erasmus Scholar on Medical Imaging and Application (MAIA) [http://maiamaster.udg.edu/]
#### For more details write me at kamruleeekuet@gmail.com
