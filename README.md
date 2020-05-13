# Concrete Crack Classification

Crack detection is important for structural health monitoring and inspection of buildings. In this project, two models were trained with images of concrete with the aim of distinguishing whether a new image has a crack or not.

The first model was a simple neural netowork with one hidden and output layer and the second model was built using Resnet18, reaching an accuracy of 99% in the test dataset.

#### Technologies used:
* Python, numpy
* Pytorch
* Convolutional Neural Networks (CNN)
* Transfer learning: Resnet18
* jupyter notebook, anaconda

## Data

The dataset consists of 40, 000  RGB images, 20,000 with cracks (positive) and 20,000 with no cracks (negative). The data can be downloaded from [Mendeley Data](https://data.mendeley.com/datasets/5y9wdsg2zt/1).

<img src="./images/concrete.jpg" width=70% height=60% align="center"> 

## Installation

Using [Anaconda](https://www.anaconda.com/products/individual), in an enviroment with python 3, install the following packages:

```
conda install -c pytorch pytorch
conda install -c pytorch torchvision
conda install numpy, matplotlib 
```

Then, run the notebook.
