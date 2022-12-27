# computer_vision

## Computer Vision Main Datasets

## 1) MNIST

#### MNIST (Modified National Institute of Standards and Technology)
MNIST is one of the first famous datasets for classification.
10 years ago MNIST was used for testing new algorihms, however, since then neural networks have learnt to fit best, and now MNIST is only used for learning purposes and minor checks. 
- Each images is sized as 28х28 pixel.
- 60000 train images and 10000 validation images.
![image](https://user-images.githubusercontent.com/18750837/209570799-10280d50-dcc3-479f-8675-a05c8632c4dc.png)


## 2) Fashion MNIST

Fashion MNIST looks similar to MNIST, and contains 60000 and 10000 images sized 28х28х1; on the pictures there are images of clothes.
![image](https://user-images.githubusercontent.com/18750837/209570796-01b036c4-7caf-4220-9327-80dce36e7ccb.png)

#### Download the datasets: https://github.com/zalandoresearch/fashion-mnist
```
features_train = np.load('/datasets/fashion_mnist/train_features.npy')
target_train = np.load('/datasets/fashion_mnist/train_target.npy')
features_test = np.load('/datasets/fashion_mnist/test_features.npy')
target_test = np.load('/datasets/fashion_mnist/test_target.npy')
```


## 3) CIFAR (Canadian Institute For Advanced Research)

#### CIFAR is a dataset with small colored images for classification problem. 
Dataset is presented into 2 versions: CIFAR-10 and CIFAR-100.

#### CIFAR-10:
- image size is 32х32х3;
- 50000 train images and 10000 test images, in total - 6000 images for each class.

#### CIFAR-100 
CIFAR-100 is similar to CIFAR-10 but is superior in coverage. It consists of 100 image classes with 600 images each. In addition, some classes are combined into superclasses, there are 20 of them in total. For example, the classes “woman” and “man” belong to the superclass “human”.
![image](https://user-images.githubusercontent.com/18750837/209570816-5a9fc56f-0b2f-48ea-a502-e92b592e1ed4.png)

## 4) ImageNet 
ImageNet is a large photo dataset that is often used to solve classification problems. It is used to compare the quality and speed of learning with different approaches, although modern neural networks cope with it too well. ImageNet is assembled during the ImageNet Large Scale Visual Recognition Challenge, which is why it is sometimes referred to as ILSVRC and labeled with the year the version was created—for example, ILSVRC2012.
Features of ImageNet:

- slightly more than 14 million images from various sources;
- two protocols: more popular with 1000 classes and more detailed with 22000 classes;
- images of different sizes in the course of training are increasingly reduced to 224x224x3;
- dataset size is approximately 170 GB.

##### ImageNet can be downloaded from official [ImageNet website](https://www.image-net.org/), [tensorflow website](https://www.tensorflow.org/datasets/catalog/imagenet2012) or [kaggle](https://www.kaggle.com/competitions/imagenet-object-localization-challenge/overview).
![image](https://user-images.githubusercontent.com/18750837/209570775-4f852c61-0c82-4336-aa62-f3678947288b.png)

## 5) MS COCO

MS COCO (Microsoft Common Objects in COntext) is a dataset compiled by Microsoft, the main benchmark in the object detection task. It is used in situations where the model needs not only to define an object, but also to highlight it with a rectangle. Thanks to the markup, it also solves a more complex segmentation problem - it separates the object from the background, highlights in detail all its pixels in the image.

Dataset features:

- 328,000 images of different sizes with different options for splitting into training, validation and test parts;
- Inside there are groups of images marked up in different ways. Some are designed for detection and segmentation of objects, 56,000 images of people have a skeleton and pose marked, and some of the images have key points and natural language captions.

MS COCO is available on the [official website](https://cocodataset.org/), where you can also find additional information about the dataset.
![image](https://user-images.githubusercontent.com/18750837/209570747-ff1287e8-cd87-4675-bb6e-df4a42b7e4e2.png)

## 6) Cityscapes

Cityscapes is a segmentation dataset of city street panoramas that is used to compare the quality of self-driving car algorithms. It contains 30 classes of objects that can be found in the images, including "road", "person", "traffic sign" and others. All classes are grouped into 8 categories.

Features of the Citiscapes dataset:
- 5,000 well-labeled datasets and 20,000 coarsely labeled images.
- The dataset was collected in 50 cities, under different weather conditions, at different times of the day and in all seasons.
![image](https://user-images.githubusercontent.com/18750837/209570906-08afc0e4-c0ab-46db-99a9-f8106b28743d.png)
![image](https://user-images.githubusercontent.com/18750837/209570925-c16080d8-5f78-4fa6-b3d8-d5eb3f6260b6.png)

### More datasets are available on [PapersWithCode](https://paperswithcode.com/datasets) or [Kaggle](https://www.kaggle.com/datasets) ML competitions.

