# Introduction

These homeworks are the part of the course AI2100 - Deep Learning offered at IIT Hyderabad in even semesters.

# HW 1

- Function to accept a 'p' and show the  $||.||_p$ norm ball 
- Function accepting a PMF and giving the entropy in bits.
- Function accepting an image and outputtng a normalised histogram.
- Function accepting a stereo image pair as an imput and outputing the normalised joint histogram
- Function accepting the joint PMF of a pair of random variables, the index of the conditioning random variable, and the value of the conditioning random variable and outputing the appropriate conditional PMF.
- Function accepting 2 PMFs and outputing the KL divergence between them.

# HW 2

- Function to output the distance betweem 2 PDFs using Cross Entropy, JS Divergence and Wasserstein Distance.
- Implementing my own version of t-SNE using the algorithm provided in the paper: https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf
- Function for convolving an image of size WxHxC with a kernel of size KxKxC with padding by reflecting the image about the axes.
- Function for correlating an image of size WxHxC with a kernel of size KxKxC with padding by reflecting the image about the axes.

# HW 3

- Convulution function that accepts as input an image, a filter kernel, stride, padding and the non-linear function. The function convolves the input image (after padding if specified) with the kernel (at the specified stride size) and generate an output activation after applying the specified non-linearity.
- Pooling function accepts as input the activation map output from the convolution function, a pooling function, and stride.
- Convolution layer function
- Pooling layer function
- Flattening (unraveling) function accepts as input the activation map volume output by the pool-ing layer and generates a vector of a specified size.
- Multilayered Perceptron (Fully Connected)
- Feed Forward Function

# HW 4
- Created a CNN using the functions defined in HW 3.
- Trained the CNN on the MNIST 
- Used a mini-batch approach to update the weights
- Backprops available: Vanilla SGD, Momentum SGD, RMSProp
- At the end of last epoch, visualized the features extracted by the network

# HW 5
- IMplemented a similar CNN as in HW 4 but using the function from PyTorch
- Used the same backprop methods
- Applied dropout and batchnormalisation

# Requirements
numpy == 1.19.2    
matplotlib == 3.3.2    
torch == 1.10.1    
torchvision == 0.11.2    
sklearn == 0.23.2   
