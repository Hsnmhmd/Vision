# Customized CNNs for Weed Groth Estimation
* In the notebook, you will find
## Data Description ,Visualization and Splitting

The data for this project are plant images at different resolutions captured with a variety of cameras. There are images showing plants with approximatelty 1,2,3,4 and 6 leafs. The images are part of a Leaf counting dataset by Teimouri et al. [1] which can be downloaded from the Aarhus University, Denmark:

<a href="https://vision.eng.au.dk/leaf-counting-dataset/">Leaf counting dataset</a>

For this work a subset of Teimouri's contains 1000 images is utilized and splitted as follows:

*  800 training
*  100 testing
*  100 validation

## Data Visualization
## Data Importing for Regression and classification and Splitting
### Auxiliary Function

## Transfer Learning - Classification Network

The first 2 blocks of the Keras implementation of VGG-16 were used in the following cell as a base blockss to build a customized CNN Classification Network to classify the images according to the number of leaves in the plant images. 

## Transfer Learning - Regression Reformulation

The customized CNN Network of the previous step is reused in the following step with modifing the last layer to treat the problem of classifing the images according to the number of leaves in the plant images as a regresssion task. 

## Discussion (Dataset Size and Base Models)
## Impact of Regularization and Data Augmantation
* Dropout Layers
* Batch Normalization

## Discussion (Regulariztion and Data Augmantation)
