# Classification of Caltech Dataset Birds
* This works makes use of mlp network and rsnet101
* The Notebook contains the following sections

## Data Description and Preparation
Dataset: <a href="http://www.vision.caltech.edu/visipedia/CUB-200-2011.html">Caltech-UCSD Birds-200-2011</a>

* A subset of 150*32 images were used for the training
* A subset of 30*32 images were used for the validation

The dataset contains annotations for various tasks. In this work, the categories for classification (species labels) were exploited.
### Data Vsiualization
### Auxiliary Function

## MLP
This section shows the implemention of a fully connected neural network (multi-layer perceptron).
- The images resize to be no larger than 32x32.
- Through, sequential model API in keras, dense layers were added 

## MLP Discussion

## ResNet-101 
### Fully Freezed ResNet101 and Transfer Learning
- Usage of transfer learning by replacing the top fully connected layer with a dense containing 200 neorons (number of categories), but leaving the other layers intact.
### ResNet101 with Unfreezed Three Layers
- three layers at different locations were unfreezed to study the impact of tuning

## ResNet Discussion

## Visualization of ResNet unfreezed Filters
This Section contains the visualization of filters of resnet that were chosen to be unfreezed with freezing and without.
To see the impact of training and tuning.
### Clusters Learned by The Model
