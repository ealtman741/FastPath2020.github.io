## Bochen  Guan, Jinnian Zhang, William A. Sethares, Richard Kijowski (*)
## Fang Liu (+)
### (*) University of Wisconsin
### (+) Harvard University

### Technical Talk: *SpecNet: Spectral Domain Convolutional Neural Network*

**Abstract:**

The memory consumption of most Convolutional Neural Network (CNN) architectures grows rapidly with increasing depth of the network, which is a major constraint for efficient network training and inference on modern GPUs with limited memory. Several studies show that the feature maps (as generated after the convolutional layers) are the main bottleneck in this memory problem. Often, these feature maps mimic natural photographs in the sense that their energy is concentrated in the spectral domain. Although embedding CNN architectures in the spectral domain is widely exploited to accelerate the training process, we demonstrate that it is also possible to use the spectral domain to reduce the memory footprint. by proposing a Spectral Domain Convolutional Neural Network (SpecNet) that performs both the convolution and the activation operations in the spectral domain. The performance of SpecNet is evaluated on two competitive object recognition benchmark tasks (CIFAR-10, and SVHN), and compared with four state-of-the-art implementations (LeNet, AlexNet, VGG, and DenseNet). Overall, SpecNet is able to reduce memory consumption by 63% without significant loss of performance for all tested networks.
