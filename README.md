# Traffic Sign Recognition
![Traffic](https://blog.mapillary.com/img/2019-06-27-mapillary-traffic-sign-dataset.png)
## Context
In this project I will explain about building a deep learning model to recognize traffic signs. It’s intended to be a learning experience, for myself and for anyone else who likes to follow along here I’ll focus on the practical aspects instead. I’ll describe my own experience building this model and share the source code. This is suitable for those who know Python and the basics of machine learning already, but want hands on experience and to practice building a real application.
In this part, I’ll explain about image classification and I’ll keep the model as simple as possible covering convolutional networks, data augmentation, and object detection.

### Problem Statement and Goal of the Project
The Dataset I have used here is the German Traffic Sign Benchmark is a multi-class, single-image classification challenge held at the International Joint Conference on Neural Networks (IJCNN) 2011.

Traffic sign detection is a high relevance computer vision problem and is the basis for a lot of applications in industry such as Automotive etc. Traffic signs can provide a wide range of variations between classes in terms of color, shape, and the presence of pictograms or text.
In this project, I will develop a deep learning algorithm that will train on German traffic sign images and then classify the unlabeled traffic signs. The deep learning model will be built using tensorflow and we will also understand various ways to preprocess images using OpenCV and also use a cloud GPU service provider.

### Breakdown of this Project:
 - Understand the data
 - Preprocess the data
 - Build the architecture of the model
 - Test the model
 - Iterate the same process until you achieve the optimal results
 - Data Understanding

### Understanding the Data

The Image dataset consists of 43 classes (Unique traffic sign images).
Training Set has 34799 Images , Test set has 12630 images and the validation set has 4410 images.

## Dataset
In this project, we use a german traffic sign dataset from [German Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)

## Conclusion
Conclusions
In this project, I applied a basic Convolution Neural Network Architecture because, it is a simple, ligh-weight with accurate results for classifying images. I wanted to try this one before anything else, and as I found that it has a great performance, in addition to the augmentation techniques.
This application will help to a self-driving car to understand, as well as we do, what comes ahead on the road and predict what actions it should have to make given the time.
