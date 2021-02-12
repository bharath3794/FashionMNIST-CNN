# Overview
Fashion-MNIST is a dataset of Zalando’s article images. This consists of 60,000 samples for training set and 10,000 samples for test set. Each sample is of 28x28 grayscale image. These samples are associated with a label from 10 classes.

## Datasets and Inputs
[Fashion-MNIST Sample Images](https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/fashion-mnist-sprite.png)

**Labels**
| Label | Description |
| --- | --- |
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |


**Train Datasets:**
[Train Images](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-images-idx3-ubyte.gz)
[Train Labels](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-labels-idx1-ubyte.gz)

**Test Datasets:**
[Test Images](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-images-idx3-ubyte.gz)
[Test Labels](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-labels-idx1-ubyte.gz)


## Libraries required to run the project

````
os
numpy
matplotlib
torch
torchvision
torchsummary
````

## Graph Visualization
Model graphs are provided in the project submission under "./runs" directory.
Library required for graph visualization:

````
tensorboard
````

**Command to visualize graphs:**

````bash
tensorboard --logdir runs
````


