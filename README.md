# Understanding-of-semantic-segmentation-using-CNN

In general, CNN for the semantic segmentation consists of two essential parts for the pixel wise classification \cite{Vijay}. The first part is encoder composed of convolutional which is responsible for the automatic features extraction \cite{min} and sub-sampling layers. The purpose of the sub-sampling layers is to achieve spatial in-variance by reducing the resolution of the feature maps which also improves the robustness of the classifier due to elimination of the redundant features. Sub-sampling also increases the field of view of the feature maps to extract more abstract class salient features and  minimizes computation time \cite{long}. On the other hand, second part is decoder to semantically project the discriminating features of lower resolution learnt by the encoder onto the pixel space of higher resolution to get a dense pixel wise classification \cite{Garcia}. In semantic segmentation, the encoder part is quite similar to all the CNN models but they mainly differ in decoder mechanism. Semantic segmentation not only requires discrimination at pixel level but also a decoder mechanism to project the discriminating features learnt at different stages of the encoder onto the pixel space. However, the significantly reduced features map due to sub-sampling, suffers spatial resolution loss which introduce coarseness, less edge information, checkerboard noise and over-segmentation in semantically segmented image \cite{long}, \cite{olaf}, \cite{odena}. When the kernel size of the deconvolution is not divisible by the up-scaling factor, the number of low resolution features that contribute to a single high resolution feature is not constant across the high resolution feature maps which is called \textit{deconvolution overlap} and is one of the cause of checkerboard artifact in segmented mask.


var justify = require('justified');

justify('Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.');


#### Written by-
#### Md. Kamrul Hasan 
#### Erasmus Scholar on Medical Imaging and Application (MAIA) [http://maiamaster.udg.edu/]
#### For more details write me at kamruleeekuet@gmail.com
