The aim of this project was to build a deep Convolutional Neural Network from scratch for the CIFAR-10 Object Classification dataset
The dataset comprises of 60,000 32x32 pixel Color photographs of objects from 10 different classes.
In the first step we developed a baseline model using the general architectural principles of VGG Models .
The model contains 3 VGG blocks .Each VGG block involves stacking convolutional layers with samall 3x3 filters followed by a max pooling layer. Padding is used on the convolution layer 
to make sure height and width of output feature maps matches the inputs .
