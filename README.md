# Image-Classification-CNN

The notebook may take a long time to load on GitHub. Use jupyter notebook viewer: [**nbviewer link**](https://nbviewer.jupyter.org/github/BonJovi1/CNN-Image-Classification/blob/master/code.ipynb)

Assignment-4, CSE578 Computer Vision, Spring 2020

- Training a CNN from scratch to classify images from the CIFAR-100 dataset with different loss functions and comparing the results. 
- Trying out different combinations of convolution, batch norm, pooling and activation layers. Trying varying learning rates and weight decay hyperparameters as well to further analyse the results. 
- Our CNN has a depth of upto 3 layers, consisting of 3 convolutional, pooling and activation layers. We apply the activation function to each convolutional layer. The pooling layer separates the convolutional layers from each other, effectively controlling any overfitting. 
- And in the last phase of the CNN network, we have a couple fo fully connected layers that have a complete connection to all the activations from the previous layers. 

We play around with this architecture, use different loss functions like cross entropy loss and KL Divergence Loss, use different activation functions, use different learning rates yada yada yada and analyse the accuracy of this image classification network! 
