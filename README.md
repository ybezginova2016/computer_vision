# computer_vision

## Computer Vision Main Datasets

## 1) MNIST

#### MNIST (Modified National Institute of Standards and Technology)
MNIST is one of the first famous datasets for classification.
10 years ago MNIST was used for testing new algorihms, however, since then neural networks have learnt to fit best, and now MNIST is only used for learning purposes and minor checks. 
- Each images is sized as 28х28 pixel.
- 60000 train images and 10000 validation images.

## 2) Fashion MNIST

Fashion MNIST looks similar to MNIST, and contains 60000 and 10000 images sized 28х28х1; on the pictures there are images of clothes.

## 3) CIFAR (Canadian Institute For Advanced Research)

#### CIFAR is a dataset with small colored images for classification problem. 
Dataset is presented into 2 versions: CIFAR-10 and CIFAR-100.

#### CIFAR-10:
- image size is 32х32х3;
- 50000 train images and 10000 test images, in total - 6000 images for each class.

#### CIFAR-100 
CIFAR-100 is similar to CIFAR-10 but is superior in coverage. It consists of 100 image classes with 600 images each. In addition, some classes are combined into superclasses, there are 20 of them in total. For example, the classes “woman” and “man” belong to the superclass “human”.

## 4) ImageNet 
ImageNet is a large photo dataset that is often used to solve classification problems. It is used to compare the quality and speed of learning with different approaches, although modern neural networks cope with it too well. ImageNet is assembled during the ImageNet Large Scale Visual Recognition Challenge, which is why it is sometimes referred to as ILSVRC and labeled with the year the version was created—for example, ILSVRC2012.
Features of ImageNet:

- slightly more than 14 million images from various sources;
- two protocols: more popular with 1000 classes and more detailed with 22000 classes;
- images of different sizes in the course of training are increasingly reduced to 224x224x3;
- dataset size is approximately 170 GB.

##### ImageNet can be downloaded from official [ImageNet website](https://www.image-net.org/), [tensorflow website](https://www.tensorflow.org/datasets/catalog/imagenet2012) or [kaggle](https://www.kaggle.com/competitions/imagenet-object-localization-challenge/overview).
