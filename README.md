# Learning

## CS-229: Stanford Machine Learning

This course provides a broad introduction to machine learning and statistical pattern recognition. 

Topics include: supervised learning (generative/discriminative learning, parametric/non-parametric learning, neural networks, support vector machines); unsupervised learning (clustering, dimensionality reduction, kernel methods); learning theory (bias/variance tradeoffs; VC theory; large margins); reinforcement learning and adaptive control. 
The course will also discuss recent applications of machine learning, such as to robotic control, data mining, autonomous navigation, bioinformatics, speech recognition, and text and web data processing.
Students are expected to have the following background:

Prerequisites: 
- Knowledge of basic computer science principles and skills, at a level sufficient to write a reasonably non-trivial computer program.
- Familiarity with the basic probability theory. (Stat 116 is sufficient but not necessary.)
- Familiarity with the basic linear algebra (any one of Math 51, Math 103, Math 113, or CS 205 would be much more than necessary.)

### Resources
* Videos, Lectures and Notes at https://see.stanford.edu/course/cs229
* Problem Sets:

| Problem Set        | Data           | Solution  | Solution Data |
| ------------- | ------------- | ----- | ----- |
| [Problem Set 1](https://see.stanford.edu/materials/aimlcs229/problemset1.pdf) | [PS1-data.zip](https://see.stanford.edu/materials/aimlcs229/PS1-data.zip) | [Solution Set 1](https://see.stanford.edu/materials/aimlcs229/ps1_solution.pdf) | [ps1_solution-data.zip](https://see.stanford.edu/materials/aimlcs229/ps1_solution-data.zip) |
| [Problem Set 2](https://see.stanford.edu/materials/aimlcs229/problemset2.pdf) | [PS2-data.zip](https://see.stanford.edu/materials/aimlcs229/PS2-data.zip) | [Solution Set 2](https://see.stanford.edu/materials/aimlcs229/ps2_solution.pdf) | [ps2_solution-data.zip](https://see.stanford.edu/materials/aimlcs229/ps2_solution-data.zip) |
| [Problem Set 3](https://see.stanford.edu/materials/aimlcs229/problemset3.pdf) | [PS3-data.zip](https://see.stanford.edu/materials/aimlcs229/PS3-data.zip) | [Solution Set 3](https://see.stanford.edu/materials/aimlcs229/ps3_solution.pdf) |   |
| [Problem Set 4](https://see.stanford.edu/materials/aimlcs229/problemset4.pdf) | [PS4-data.zip](https://see.stanford.edu/materials/aimlcs229/PS4-data.zip) | [Solution Set 4](https://see.stanford.edu/materials/aimlcs229/ps4_solution.pdf) | [ps4_solution-data.zip](https://see.stanford.edu/materials/aimlcs229/ps4_solution-data.zip) |

## CS-231n: Convolutional Neural Networks for Visual Recognition

Computer Vision has become ubiquitous in our society, with applications in search, image understanding, apps, mapping, medicine, drones, and self-driving cars. Core to many of these applications are visual recognition tasks such as image classification, localization and detection. Recent developments in neural network (aka “deep learning”) approaches have greatly advanced the performance of these state-of-the-art visual recognition systems. This course is a deep dive into details of the deep learning architectures with a focus on learning end-to-end models for these tasks, particularly image classification. During the 10-week course, students will learn to implement, train and debug their own neural networks and gain a detailed understanding of cutting-edge research in computer vision. The final assignment will involve training a multi-million parameter convolutional neural network and applying it on the largest image classification dataset (ImageNet). We will focus on teaching how to set up the problem of image recognition, the learning algorithms (e.g. backpropagation), practical engineering tricks for training and fine-tuning the networks and guide the students through hands-on assignments and a final course project. Much of the background and materials of this course will be drawn from the ImageNet Challenge.

### Resources
* 2017 Lecture Videos: https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv
* Chinese Version: https://space.bilibili.com/216720985/channel/detail?cid=32406
* Assignments:

| Assignments (Spring 2018) |
| ------ |
| [Assigment 1: kNN, SVM, SoftMax, two-layer network](http://cs231n.github.io/assignments2018/assignment1/) |
| [Assigment 2: Neural networks, ConvNets](http://cs231n.github.io/assignments2018/assignment2/) |
| [Assigment 3: RNN, GAN, Style transfer, etc.](http://cs231n.github.io/assignments2018/assignment3//) |

* Notes (helpful for assignments):

[Python Numpy Tutorial](http://cs231n.github.io/python-numpy-tutorial/)

[kNN](http://cs231n.github.io/classification/)

[Linear Classification](http://cs231n.github.io/linear-classify)

[Optimization](http://cs231n.github.io/optimization-1)

[Backpropagation](http://cs231n.github.io/optimization-2)

[ConvNets](http://cs231n.github.io/convolutional-networks/)

Neural Networks: [1](http://cs231n.github.io/neural-networks-1/), [2](http://cs231n.github.io/neural-networks-2/), [3](http://cs231n.github.io/neural-networks-3/)

# Frameworks
* Tensorflow

[Tutorials](https://www.tensorflow.org/tutorials), [Keras](https://www.tensorflow.org/guide/keras), [Using GPU](https://www.tensorflow.org/guide/using_gpu), [Tensorboard](https://www.tensorflow.org/guide/summaries_and_tensorboard)

* PyTorch

[Tutorials](https://pytorch.org/tutorials/)

# Environments

Using Anaconda with python 3.7 is recommended. https://www.anaconda.com/distribution/

```shell
# Replace the link with proper version
wget https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
sh ./Anaconda3-2019.03-Linux-x86_64.sh
```

* Installing tensorflow:

```shell
conda install tensorflow-gpu
# tenorflow-gpu 1.13.0 only support CUDA 10.0+, which is incompatible with NVIDIA driver version 
# lower than 400. If 1.13.0 not work, try an older version
conda install tensorflow-gpu==1.X.X
```

* Installing pytorch:
```shell
conda install pytorch torchvision cudatoolkit=10.0 -c pytorch
#                                 cudatoolkit=9.0
#                                 cudatoolkit=8.0
```

