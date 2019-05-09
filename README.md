# Understanding-of-semantic-segmentation-using-CNN

In general, CNN for the semantic segmentation consists of two essential parts for the pixel wise classification to assign the pixel labels. The first part is encoder composed of convolutional which is responsible for the automatic features extraction and sub-sampling layers. The purpose of the sub-sampling layers is to achieve spatial in-variance by reducing the resolution of the feature maps which also improves the robustness of the classifier due to elimination of the redundant features. Sub-sampling also increases the field of view of the feature maps to extract more abstract class salient features and  minimizes computation time. Sometimes, dropout layer or batch normalization or even both are added after each convolution to avoid the overfitting and to make the robust pixel wise classifier. On the other hand, second part is decoder to semantically project the discriminating features of lower resolution learnt by the encoder onto the pixel space of higher resolution to get a dense pixel wise classification. In semantic segmentation, the encoder part is quite similar to all the CNN models but they mainly differ in decoder mechanism. Semantic segmentation not only requires discrimination at pixel level but also a decoder mechanism to project the discriminating features learnt at different stages of the encoder onto the pixel space. However, the significantly reduced features map due to sub-sampling, suffers spatial resolution loss which introduce coarseness, less edge information, checkerboard noise and over-segmentation in semantically segmented image. When the kernel size of the deconvolution is not divisible by the up-scaling factor, the number of low resolution features that contribute to a single high resolution feature is not constant across the high resolution feature maps which is called deconvolution overlap and is one of the cause of checkerboard artifact in segmented mask.

## Useful links for understanding semantic segmentation 
- [x] Title: How to do Semantic Segmentation using Deep learning <br>
      Link : https://medium.com/nanonets/how-to-do-image-segmentation-using-deep-learning-c673cc5862ef
      
- [x] Title: Semantic Segmentation using CNN’s <br>
      Link : https://medium.com/@aiclubiiitb/semantic-segmentation-using-cnns-357fbcfa1bc     
      
- [x] Title: Semantic Segmentation with Deep Learning <br>
      Link : https://towardsdatascience.com/semantic-segmentation-with-deep-learning-a-guide-and-code-e52fc8958823

- [x] Title: Semantic Segmentation: Introduction to the Deep Learning Technique Behind Google Pixel’s Camera! <br>
      Link : https://www.analyticsvidhya.com/blog/2019/02/tutorial-semantic-segmentation-google-deeplab/ 
      
- [x] Title: Computer Vision Tutorial: A Step-by-Step Introduction to Image Segmentation Techniques <br>
      Link : https://www.analyticsvidhya.com/blog/2019/04/introduction-image-segmentation-techniques-python/

- [x] Title: Semantic Segmentation of Aerial images Using Deep Learning <br>
      Link : https://towardsdatascience.com/semantic-segmentation-of-aerial-images-using-deep-learning-90fdf4ad780
      
- [x] Title: How to use DeepLab in TensorFlow for object segmentation using Deep Learning <br>
      Link : https://medium.freecodecamp.org/how-to-use-deeplab-in-tensorflow-for-object-segmentation-using-deep-learning-a5777290ab6b
      
      
      
## Understanding of U-Net

- [x] Title: U-Net: Convolutional Networks for Biomedical Image Segmentation <br>
      Link : https://arxiv.org/abs/1505.04597
      
- [x] Title: Understanding Semantic Segmentation with UNET <br>
      Link : https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47

- [x] Title: Medical Image Segmentation [Part 1] — UNet: Convolutional Networks with Interactive Code <br>
      Link : https://towardsdatascience.com/medical-image-segmentation-part-1-unet-convolutional-networks-with-interactive-code-70f0f17f46c6
      
- [x] Title: U-Net <br>
      Link : http://www.deeplearning.net/tutorial/unet.html
      
 - [x] Title: Learn How to Train U-Net On Your Dataset <br>
      Link : https://medium.com/coinmonks/learn-how-to-train-u-net-on-your-dataset-8e3f89fbd623
      
 - [x] Title: Practical image segmentation with Unet <br>
      Link : https://tuatini.me/practical-image-segmentation-with-unet/
      
 - [x] Title: Get acquainted with U-NET architecture + some keras shortcuts <br>
      Link : https://spark-in.me/post/unet-adventures-part-one-getting-acquainted-with-unet
      
      
      
## Understanding of Fully Convolutional Networks (FCN)

- [x] Title: Fully Convolutional Networks (FCN) for 2D segmentation <br>
      Link : http://www.deeplearning.net/tutorial/fcn_2D_segm.html
      
      
- [x] Title: Review: FCN — Fully Convolutional Network (Semantic Segmentation) <br>
      Link : https://towardsdatascience.com/review-fcn-semantic-segmentation-eb8c9b50d2d1

- [x] Title: Fully Convolutional Networks (FCNs) for Image Segmentation <br>
      Link : http://warmspringwinds.github.io/tensorflow/tf-slim/2017/01/23/fully-convolutional-networks-(fcns)-for-image-segmentation/
      
      
- [x] Title: Semantic Segmentation using Fully Convolutional Networks over the years <br>
      Link : https://meetshah1995.github.io/semantic-segmentation/deep-learning/pytorch/visdom/2017/06/01/semantic-segmentation-over-the-years.html
      

- [x] Title: Fully Convolutional Networks for Semantic Segmentation <br>
      Link : https://paperswithcode.com/paper/fully-convolutional-networks-for-semantic


- [x] Title: Fully Convolutional Networks (FCN) <br>
      Link : https://d2l.ai/chapter_computer-vision/fcn.html
      

- [x] Title: How is Fully Convolutional Network (FCN) different from the original Convolutional Neural Network (CNN)? <br>
      Link : https://www.quora.com/How-is-Fully-Convolutional-Network-FCN-different-from-the-original-Convolutional-Neural-Network-CNN
      

### Understanding Region-based Fully Convolutional Networks (R-FCN) for object detection
- [x] Link: https://medium.com/@jonathan_hui/understanding-region-based-fully-convolutional-networks-r-fcn-for-object-detection-828316f07c99 
      
      
      
## Github Source code link
- [x] Title: Awesome Semantic Segmentation <br>
      Link : https://github.com/mrgloom/awesome-semantic-segmentation





#### Written by-
#### Md. Kamrul Hasan 
#### Erasmus Scholar on Medical Imaging and Application (MAIA) [http://maiamaster.udg.edu/]
#### For more details write me at kamruleeekuet@gmail.com
