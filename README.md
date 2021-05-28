# LeNet-5: a boundary completion study
 
It is widely accepted that the convolutional layers in a wide range of CNN's could closely resemble simple and complex cells populations in the mammalian brain. In particular their weight distribution seems to converge to a Gabor filter shape.

In this work we explore these phenomenons in more depth, focusing in particular on the ability of the network to recognize partially occluded or misleading digits (does the net see illusory boundaries? how does it complete them?).

Dataset: `torchvision.datasets.MNIST()`

Model: LeNet-5 (from LeCun, Y. et al. “Gradient-based learning applied to document recognition.” (1998) - https://axon.cs.byu.edu/~martinez/classes/678/Papers/Convolution_nets.pdf".
