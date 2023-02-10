##Introduction

In both theory and practice, we have achieved our main goal of implementing applied 
machine learning "CNN - Fruit recognition from images". Understand how to analyze the
system and apply the algorithm model to the system. We need to get a lot of records for 
each image.

##Theory

CNNs are a type of deep learning model. Convolutional layers, pooling layers, 
ReLU layers, fully linked layers, and loss layers are all possible components of such 
a network. Each convolutional layer is followed by a Rectified Linear Unit (ReLU) 
layer, a Pooling layer, one or more convolutional layers, and eventually one or more 
fully connected layers in a conventional CNN design. The CNN differs from a 
typical neural network in that it considers the structure of the pictures when 
processing them. A regular neural network turns input into a one-dimensional array, 
making the trained classifier less sensitive to changes in position. Using multicolumn deep neural networks yielded some of the top results on the MNIST dataset. 
They employ many maps per layer with numerous layers of non-linear neurons, as 
stated in paper. Even if the intricacy of such networks makes training them more 
difficult, graphics processors and specially crafted programming can help. The 
network's structure employs winner-take-all neurons with maximum pooling to find 
3
the winning neurons. Another article supports the notion that convolutional 
networks have improved accuracy in the field of computer vision. An allconvolutional network with excellent performance on CIFAR-10 is presented in full 
in article. Pooling and fully connected layers are proposed to be replaced by 
comparable convolutional layers in the article. This increases the amount of 
parameters and inter-feature connections, but it may be decreased by employing 
smaller convolutional layers inside the network, which functions as a type of 
regularization. Each layer of a CNN network will be described in the following 
sections.
