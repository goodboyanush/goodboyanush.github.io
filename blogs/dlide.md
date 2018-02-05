# DL-IDE - A Visual IDE for Deep Learning

## Why DL-IDE?

Deep learning is one of the most exciting and active research area in the machine learning community. Deep learning has created almost a revolution and has yielded state-of-the-art performance in various research fields, including computer vision, speech processing, and text analytics. Various libraries/frameworks have surely contributed to this growth. Some of the widely used deep learning libraries are CAFFE, Tensorflow, Theano, Keras, Torch, and MxNet.

However, the existing libraries such as Tensorflow, Theano, Torch, Caffe, Keras etc. has the following broader challenges:

1. requires an initial large learning curve
2. knowledge of deep learning fundamentals is mandatory
3. Each library has a different syntax and has minimum communication across them. 

There is a need for simple intuitive tools to cater the needs of the diverse communities and enable them to implement and prototype deep learning models in a quicker fashion. Thus, to overcome these challenges and to make deep learning further approachable and accessible to larger audience, even to non-experts, we at IBM Research, India have launched a new IDE for deep learning called IBM Deep Learning IDE (DL-IDE).

## What is DL-IDE?

IBM Deep Learning IDE (DL-IDE) a visual programming IDE, where the users could design a deep learning model using an intuitive drag-and-drop framework.  It is a creative system that could automatically write the execution ready deep learning code in Tensorflow, CAFFE, and Theano using the input, without the users having to actually write a single line of code. Thus, DL-IDE helps to flatten out the learning curve, particularly, related to understanding the specific deep learning libraries. This tool helps in extreme rapid prototyping of deep learning models and implementation of state of art papers.

Further, researchers often are interested in plugging in the publicly shared implementations in their code base. However, due to availability of various libraries and programming languages the simple task of plugging-in might be challenging. For example, a public implementation of a face recognition algorithm might be available in CAFFE, while, the user might be interested in a Tensorflow implementation of the same. In DL-IDE, one can import the code written in CAFFE (prototxt files) and export it the same code in Tensorflow. This has potentials of faster code adaptation for wider audience. 

## DL-IDE Demo

> [What is this IDE all about?](https://www.youtube.com/watch?v=k-UygtFy8Q8)

> [How to implement DeepID paper using DL-IDE](https://www.youtube.com/watch?v=k-UygtFy8Q8&t=108s)

> [DeepID Caffe Code to DL-IDE](https://www.youtube.com/watch?v=k-UygtFy8Q8&t=193s)

## How to access?

The current version of the tool is available at: [DL-IDE](https://dlide.mybluemix.net/). It is a free to use tool, and even a registration is not required. It could be directly used by a simple Google sign in.

## Note

Kindly note that the IBM Deep Learning IDE (DL-IDE) was previous called as DARVIZ. Both refer to the same system.