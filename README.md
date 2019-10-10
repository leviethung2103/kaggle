## Digit Recognizer - Kaggle Competition

### Competition Description

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.


### My approach

I use the Resnet34 as the backbone network. Fastai is the new library based on pytorch. I use that because of fast idea facilitation.

Another approaches are using SVM classifier, simple neural network with only 5 convolutional neural networks. 

This is my first project on Kaggle to practice tunning hyperparameters, creating some fancy models, getting insight of many datasets. 

Download Datasets I've created at: https://drive.google.com/file/d/1qvwEx36fjehIntfdFDDWLIrsuFd7c6dk/view?usp=sharing

Unzip the dataset, then we have 2 folders `train` and `test` 

The code is written in jupyter notebook. 

I've got 96.757 % accuracy in digit detection

![/img/Selection_045](/img/Selection_045.png
)

After tunning number of epochs, I got the new record. The new accuracy is 98.58%. The number of epochs is 20. 

![/img/Selection_046](/img/Selection_046.png
)

The performance after setting 50 epochs. 

![/img/Selection_047](/img/Selection_047.png
)

I haven't tried the data augmentation. Therefore, I would try it in the next version 













