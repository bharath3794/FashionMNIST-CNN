## Performance on Test set
epoch #19: Average loss: 0.2089, Accuracy: 1884/2000 (94.20%)

## Dataset
**Train Datasets:**
[Train Images,](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-images-idx3-ubyte.gz)
[Train Labels](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-labels-idx1-ubyte.gz)

**Test Datasets:**
[Test Images,](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-images-idx3-ubyte.gz)
[Test Labels](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-labels-idx1-ubyte.gz)

## Sample Images
![Fashion-MNIST Sample Images](https://github.com/bharath3794/FashionMNIST-CNN/blob/main/images/sample%20image.png)

## Train, Validation & Test Split
![split](https://github.com/bharath3794/FashionMNIST-CNN/blob/main/images/train_valid_test%20split.png)

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
Model graphs are provided in the project "./runs" directory.
Library required for graph visualization:

````
tensorboard
````

**Command to visualize graphs:**

````bash
tensorboard --logdir runs
````

## Evaluation & Graphs
### Loss
![loss](https://github.com/bharath3794/FashionMNIST-CNN/blob/main/images/loss%20graph.PNG)

### Accuracy
![accuracy](https://github.com/bharath3794/FashionMNIST-CNN/blob/main/images/accuracy%20graph.PNG)

## Model Summary
![PyTorch](https://github.com/bharath3794/FashionMNIST-CNN/blob/main/images/model%20summary.PNG)

