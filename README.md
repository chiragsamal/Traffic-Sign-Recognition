# Traffic Sign Recognition

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
