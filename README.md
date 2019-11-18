# EIP
```
print(score)
[0.03684927592134036, 0.9916]
```
# Convolution
Convolution is basically a mathematical opertion which is applied on two different funtion let say one is f and other one ig g. Once the convolution is done on these two function it result in a new function or an output which has details about how the previous functions have effected each other. 

# Filters/Kernels 
Filters or kernels are the most import part of convolutional neural network. They extract the fatures of an images like vertical line, horizonta line, round part in the impage, dark part of animage etc. Most common used kernel is 3 x 3 

# Epochs 
Epochs are the number of times for which the neural network has to go through the dataset. So let say we have a dataset of 100 images and epoch is 2 so the neiral netrork would iterate through 100 datapoints for 2 times in order to learn the network and features


# 1x1 Convolution 
1 x 1 convolution is basically  used in neural network for andling the features.
It is a mapping between an input pixel with all it's channels to an output pixel. It is often used to reduce the number of depth channels.


# 3x3 Convolution
 3 x 3 convolution is the most common used kernel or filter in the neural network. It can be considered as most the basic but yet powerful filter. We can also say that other kernels are made from 3 x 3 filter or they are the result of such 3 x 3 filters

# Feature Maps
It is also called as the activation map. It is basically the the mapping of different part of the image i.e the different features in an image like curves, shades etc

# Activation Function 
Activation function are one of the most import part pf a neural network which helps to make or convert an linear relationship in a network to non linear.
Different types of activation function are used for different situations. 
ReLu, SeLu etc

# Receptive Field 

In a CNN the response of kernel or filter is a response or features extracted form the image which need to be passed to the next subsequent layer and so on. So tht the multiple layer is able to read the feature of current neurons as well as the previous extracted fetures. The area of the previous layer that a filter is applied is called the receptive field of that neuron.

