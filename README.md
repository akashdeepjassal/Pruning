# Model Prunning Assignment

# What is Prunning

Pruning is a  deep learning technique that helps in the development of smaller and efficient models. 
It’s a model optimization technique that involves elimination of unnecessary values in the weights. 
This creates a compressed neural networks that run faster, reduces the computational cost involved during training of the networks. 
It is even more crucial when deploying models to mobile phones or other edge devices. 

### Some Techniques
The notebook uses torch.nn.utils.prune to sparsify your neural networks, and how to extend it to implement your own custom pruning technique.
There are a lot of new techniques in prunning which have been deevloped and are being researched on.
Pruning from Scratch is a popular method and is implemeted in the notebook. A lot of new methods have been proposed like Adversarial Neural Pruning, Filter Pruning using High-Rank Feature Map, Dynamic Model Pruning with Feedback etc.

### Some Sources
* Major Pruning Papers https://github.com/chenbong/awesome-compression-papers
* https://www.tensorflow.org/model_optimization/api_docs/python/tfmot
* https://jacobgil.github.io/deeplearning/pruning-deep-learning
* https://heartbeat.fritz.ai/research-guide-pruning-techniques-for-neural-networks-d9b8440ab10d#:~:text=Pruning%20is%20a%20technique%20in,values%20in%20the%20weight%20tensor.

###Outputs

![For Conv Model](model_conv.png?raw=true "Conv Model")
![For Dense Model](model_dense.png?raw=true "dense Model")

#### More Changes Coming
