# Aptos2019 Kaggle competition portfolio

This is my first kaggle competition, it is a good chance to practice my newly aquired skills in computer vision to help detecting blindness. The official competition website is here:
https://www.kaggle.com/c/aptos2019-blindness-detection

In this competition, I have spend a lot of hours to try out new modeling techniques and I do borrow some notebook with top performance to essemble with my models. Below is the summary of the efforts spent:

* 3 major modelling strategies tested
* Google cloud computing
* 6 CNN network implemented
* 10 data augmentation techniques 
* 630 GPU hours run

## Research question formulation

* Classification (to address the differences between images)
* Linear regression (to address the progression in the images)
* Ordinal Classification (multilable classification for images)


## CNN used in the project

* EfficientNet B5/B0
* ResNet50
* Resnet34
* DenseNet121
* Wide Resnet50 -2 - BottleNeck

## Highest scoring notebook selected after submission deadline

The highest score notebook were actually not submitted as I have two many notebooks to choose from and inexperienced in selecting the notebook that would fit the private data set best.

This is an ensemble method, as the kaggle kernel session runs only 9 hours, I have to split the process into two separate kernels. The main kernel is developed in the below link:

https://www.kaggle.com/haowumelbourne/linear-with-mix-up-retrain-cycle?scriptVersionId=19697276

The pre-trained model used in this notebook were developed in the below notebook:

https://www.kaggle.com/haowumelbourne/linear-with-mix-up-retrain-cycle?scriptVersionId=19652223

This folder will contain other notebooks used in google cloud which used for setting up models or running sessions that would be longer than 9 hours.


